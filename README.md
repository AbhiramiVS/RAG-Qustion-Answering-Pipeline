# RAG-Qustion-Answering-Pipeline

A Retrieval Augmented Generation Pipeline using Lang chain framework.

## To run:

- Install requirements using pip install -r requirements.txt

- "data" folder is where we are adding the documents for RAG pipeline, so add your data in that folder. Currently, this pipeline is equipped to read pdf files, so please use pdf files.

- Run the code using python query_data.py

To run this pipeline, you need to provide huggingface api token. Follow below site to get your api token.
https://huggingface.co/docs/hub/security-tokens

Once you have your tocken, update line no: 13, in query_data.py with your api token.

Here Mistral-7B-Instruct-v0.1 Large Language Model (LLM) is used for Generation part, follow the below link to know more about it. 
https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1

I am using Chroma vector store from Langchain, if you want to read more about vector stores,
https://python.langchain.com/docs/modules/data_connection/vectorstores/
