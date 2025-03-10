# Gen-AI

# Problem Statement: Automated Data Query and Retrieval System Using Offline(free & open source) Large Language Models With CSV, MongoDB, LlamaIndex, and LangChain

Requirements or Steps to Follow
  1. CSVData Management:
     1. Youwill be provided with a CSV file containing various columns of data.
     2. Your first task is to write a Python script to load this data into a MongoDB collection.
     3. Each row of the CSV should be stored as a separate document in the MongoDB database.

  2. Dynamic Query Generation using LLM:
     1. The next step involves building a Python-based interface where the user can input the name of a CSV column header.
     2. Based on the user's input, you will use an LLM to generate a MongoDB query that can retrieve relevant data from the database.
     3. Ensure that the generated query is both syntactically correct and logically sound for the given input.

3. Data Retrieval and Presentation:
   1. Execute the MongoDB query generated by the LLM to fetch the required data from the database.
   2. Oncethe data is retrieved, you have two options for presenting it:
     ■ Display the Data: Present the data to the user in a human-readable format (e.g., a table or printed output).
     ■ Save the Data: Save the retrieved data back into a new CSV file that the user can download or view.Give names to files as per test cases.(ex. test_case1.csv etc)

# Overview

This project implements an Automated Data Query and Retrieval System using offline large language models (LLMs) and various data-handling tools. It integrates MongoDB, CSV processing, LlamaIndex, and LangChain to dynamically generate and execute database queries based on user input.

# Features

1. CSV Data Management: Load structured data from CSV into MongoDB.
2. Dynamic Query Generation: Use LLMs (GPT4All) to convert user questions into MongoDB queries.
3. Data Retrieval & Presentation: Execute queries and present data in a structured format.
4. Offline AI Integration: Use GPT4All and LangChain for local AI-based query processing.

# Installation & Setup
     1. Set Up MongoDB
     2. Install Dependencies  
         pip install pymongo pandas tkinter llama-index langchain_community gpt4all transformers sentence-transformers

# Dependencies

The project uses the following Python libraries:
1. pymongo → MongoDB interaction
2. pandas → CSV handling
3. tkinter → GUI (for file selection)
4. llama-index → Data retrieval and indexing
5. langchain_community → LLM integration
6. gpt4all → Offline LLM execution
7. transformers → Model handling
8. sentence-transformers → Embedding generation

# Troubleshooting

  1. MongoDB Connection Error: Ensure MongoDB is running (mongod command).
  2. Model Loading Issue: Manually download GPT4All models and place them in ~/.cache/gpt4all/.
  3. Missing Dependencies: Run pip install -r requirements.txt if needed.

# Outputs
![Image](https://github.com/user-attachments/assets/b22748f1-dc71-4da6-90f0-2c43e086f3fa)
![Image](https://github.com/user-attachments/assets/1c37614d-c77e-4141-bdaf-750b4a6491af)
