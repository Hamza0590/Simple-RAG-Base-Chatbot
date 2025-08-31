# RAG-Based Chatbot Simple

A lightweight **RAG (Retrieval-Augmented Generation) based chatbot** built in Python. This chatbot allows users to query their documents (PDF, text, or DOC files) and get context-aware answers using an LLM.  

---

## Features

- Query your documents and get answers in natural language.  
- Supports **PDF, DOC, and TXT** file formats.  
- Customize chunk size and overlap for document processing.  
- Configure how many context paragraphs to retrieve for precise answers.  
- Simple setup and usage; all dependencies can be installed with a single run.  

---

## Requirements

- Python 3.8 or higher  
- All required libraries are installed via the first cell in the notebook/script.  

---

## Setup Instructions

1. **Weaviate Account:**  
   - Create a free account on [Weaviate](https://weaviate.io/).  
   - Create a **cluster** and generate an **API key**.  
   - Copy the **endpoint/URL** and **API key**.  

2. **Configure Script:**  
   - Paste the Weaviate **URL** and **API key** in the designated block in the code.  
   - Run the first cell to install all dependencies.  

3. **Provide Documents:**  
   - In the final block of the script, provide the path to your PDF/DOC/TXT file.  

4. **Querying:**  
   - Change the `query` variable to ask your question.  
   - By default, chunk size = 500, overlap = 100, and number of context paragraphs = 2.  
   - These values can be customized by passing arguments to the respective functions.  

5. Example Image:  ![RAG Chatbot Diagram](images/Screenshot_2025-08-31_212254.png)


