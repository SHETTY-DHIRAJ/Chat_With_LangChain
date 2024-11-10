# Chat With LangChain

This project explores how to use **LangChain** to interact dynamically with data using two key approaches: **Retrieval Augmented Generation (RAG)** and **Question-Answer Chatbots**. By integrating RAG, we leverage external datasets to generate contextually enriched responses. The project focuses on building a chatbot that can respond accurately to questions based on the specific content of the provided documents and previous conversations (chat history).

## Process Overview

![Process_Overview](https://github.com/SHETTY-DHIRAJ/Chat_With_LangChain/blob/main/Process_Overview.jpeg)
Image credit: [LangChain Chat with Your Data](https://www.coursera.org/projects/langchain-chat-with-your-data-project) on Coursera

## Features

This repository includes six core tasks, each implemented in separate Jupyter notebooks:

a. **Document Loading**  
   - Understand the essentials of data loading.
   - Access unique data loaders to retrieve data from various sources, including audio and video.

b. **Document Splitting**  
   - Explore best practices and considerations for document segmentation, crucial for handling large datasets and improving retrieval accuracy.

c. **Vector Stores and Embeddings**  
   - Learn the concept of embeddings and how to store them efficiently in vector databases, with seamless integration into LangChain.

d. **Retrieval**  
   - Discover techniques for indexing and retrieving data from the vector store, going beyond basic semantic searches to fetch the most relevant information.

e. **Question Answering**  
   - Build a one-pass question-answering model, utilizing vectorized retrieval to answer questions based on your dataset.

f. **Chat**  
   - Develop a chatbot capable of tracking and selecting relevant information from both previous conversations (chat history) and data sources, enabling interactive Q&A with your documents.
   
## Project Structure

- **Notebooks**  
  Each task is implemented in a dedicated Jupyter notebook:
  - `01_Document_Loading.ipynb`
  - `02_Document_Splitting.ipynb`
  - `03_Vector_Stores_and_Embeddings.ipynb`
  - `04_Retrieval.ipynb`
  - `05_Question_Answering.ipynb`
  - `06_Chat.ipynb`

- **Data**  
  Ensure you have a data directory with documents or data sources for chatbot interaction.


## Prerequisites

- Python 3.8 or higher
- Jupyter Notebook for interactive code exploration.
- LangChain: A framework that simplifies LLM applications.
- Embedding: A embedding model is needed to be installed.
- Vector Database- chroma for efficient storage and retrieval of embeddings.

## How It Works

- Load and preprocess your documents.
- Split them for optimal storage and retrieval.
- Embed the data and store in a vector database.
- Use RAG to retrieve and answer questions with context.
- Interact with your chatbot, which draws answers based on your custom dataset and previous interactions using chat history.
## Acknowledgements

 - This project was inspired and developed based on the concepts learned in the [LangChain Chat with Your Data](https://www.coursera.org/projects/langchain-chat-with-your-data-project) on Coursera. Special thanks to the course creators for their comprehensive content and guidance in applying Retrieval Augmented Generation and chatbot development with LangChain.


## Contributing

Contributions are always welcome!
