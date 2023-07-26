# LLM-lang-chain-NLP-information-Data_Retrieval-retriavl

This project is an innovative application of Natural Language Processing (NLP) and Machine Learning (ML) techniques to retrieve financial data. The primary objective is to extract and structure financial data from unstructured sources, and then use this data to answer user queries about specific financial metrics or trends. The project leverages the power of OpenAI's GPT-3, HuggingFace's Transformers, and other state-of-the-art NLP models to process and understand the data.

The project begins with the extraction of financial data from various sources, including CSV files and text documents. This data is then processed and structured using Python's powerful data manipulation libraries, such as pandas. The structured data is then transformed into an unstructured format, which is more suitable for NLP tasks. This transformation involves creating a narrative for each data point, which includes details such as the stock symbol, security name, date, opening price, closing price, and other relevant information.

The unstructured data is then fed into a language model, which is trained to understand and answer queries about the data. The project uses a combination of different strategies, including OpenAI's GPT-3, HuggingFace's Transformers, and InstructorEmbedding, to generate embeddings for the data and to answer queries. The project also uses the FAISS library for efficient similarity search to retrieve the most relevant documents for a given query.

The final output of the project is a conversational AI that can answer complex financial queries with high accuracy. This AI can be used in various applications, such as financial analysis, investment decision-making, and financial education. The project demonstrates the power of NLP and ML in transforming raw, unstructured data into valuable insights and information.
# Requirments and libraries 

This project utilizes a variety of Python libraries and dependencies to handle different aspects of data processing, machine learning, and natural language processing. Here's a comprehensive list:

Pandas: This library is used for data manipulation and analysis. It is particularly useful for manipulating numerical tables and time-series data.

Glob: The glob module is used to retrieve files/pathnames matching a specified pattern.

OS: This module provides a way of using operating system dependent functionality, like reading or writing to the file system.

Zipfile: This module is used for reading and writing ZIP archive files.

OpenAI: This library is used to interact with the OpenAI API and leverage the GPT-3 model for natural language processing tasks.

HuggingFace's Transformers: This library provides state-of-the-art machine learning models for NLP tasks. It is used to leverage transformer models like T5.

HuggingFace's Sentence Transformers: This library provides an easy method to compute dense vector representations for sentences and paragraphs.

InstructorEmbedding: This is a custom library used to generate embeddings for the data.

FAISS (Facebook AI Similarity Search): This library is used for efficient similarity search and clustering of dense vectors.

Langchain: This library is used to build conversational AI models. It provides various components like document loaders, text splitters, embeddings, vector stores, and chains.

Accelerate and BitsandBytes: These libraries are used to accelerate the training process of machine learning models.

Tiktoken and ChromaDB: These libraries are used to work with tokens in the context of OpenAI's models.

HuggingFaceHub: This library is used to interact with the HuggingFace Model Hub.
