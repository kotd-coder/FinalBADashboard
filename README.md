Business/ Finance News AI Assistant:
By Tyler Ko

This project is an interactive AI assistant that utilizes a RAG, Hugging face models, and a Finance news API, all combined into one Gradio interface.
It allows users to ask a business analytics and current finance news questions and get:
Business Analyst Responce: From a repository of Business Analystics focused PDF documents using a RAG pipeline
Finance API Responce: With live financial news from an external API

RAG Features:
PDF's are loaded from BA_docs directory,
Documents are chuncked (1500 tokens, 200 overlap),
FLAN t5 large model

GUI:
Input box for questions,2 outputs(Business analyst RAG and Finance API Responces)

How to utilize:
1. Place PDF's in folder:BA_docs
2. Run notebook
3. Open Web app
