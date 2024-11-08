# Askmedata

A SQL based Chatbot using Langchain

Created a Chatbot which converts text input to a SQL query which runs on SQL database using Google Palm of LangChain. Did Few shot learning for selected queries and embedded them into vectors using HuggingFace. Stored them in ChromaDB database. For every query, the model fails it looks for similar queries in the database to give results. Created a better UI using Streamlit.
