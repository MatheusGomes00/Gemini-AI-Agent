# Projeto Agente de IA com Gemini

## Descrição
Projeto criado durante a **Imersão Alura – Agentes de IA**, utilizando a **IA gratuita do Google Gemini**.  
O agente desenvolvido simula um **assistente de triagem de conversas** para uma empresa fictícia. Ele é capaz de:
- Interagir com o usuário;
- Consultar políticas fornecidas via **RAG (Retrieval-Augmented Generation)**;
- Tomar decisões a partir dessas políticas.

---

## Tecnologias utilizadas
- **Python 3**
- **LangChain**
- **langchain-google-genai**
- **Google Generative AI (Gemini)**
- **Google Colab**

---

## Instalação
Para executar o projeto no Colab:

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/imersao-alura-agentes-ia.git
cd imersao-alura-agentes-ia
````

2. Inporte o arquivo Imersão_Agentes_de_IA_Alura_+_Google_Gemini.ipynb no seu ambiente do 
Google Colab.

3. Configure uma **API Key** no ambiente do colab chamada "GEMINI_API_KEY". Para utilizar outra
denominação basta alterar o valor da variável 'GOOGLE_API_KEY' da célula 2 de código do notebook:
```
from google.colab import userdata
from langchain_google_genai import ChatGoogleGenerativeAI

GOOGLE_API_KEY = userdata.get('GEMINI_API_KEY')
``` 

4. Na pasta [politicasRAG](./politicasRAG/) importe os arquivos de política gerados para teste. No ambiente colab os arquivos ficam no diretório '/content/', basta fazer o upload dos arquivos da pasta citada. !Note: Os arquivos são excluídos assim que o ambiente é encerrado.

5. Execute as células de código.

---


