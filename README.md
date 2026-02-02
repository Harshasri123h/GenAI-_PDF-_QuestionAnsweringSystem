# 📄 GenAI PDF Question Answering System
📌 Overview

Large documents such as reports, policies, and study materials are often difficult to search and analyze efficiently. Manually reading PDFs to find specific information is time-consuming and error-prone.

This project implements a Generative AI–based PDF Question Answering System that enables users to upload PDF documents and ask natural language questions to quickly retrieve relevant, context-aware answers.
![image](https://github.com/Niez-Gharbi/PDF-RAG-with-Llama2-and-Gradio/assets/57814219/29efb4c9-1f15-479a-a57b-34bdd2085068)


PDFChatBot is a Python-based chatbot designed to answer questions based on the content of uploaded PDF files. It utilizes the Gradio library for creating a user-friendly interface and LangChain for natural language processing.

## Technologies Used 🚀
* Langchain
* Llama2
* ChromaDB
* Hugging Face
* Gradio
🎯 Problem Statement

Business users and students frequently need to extract specific insights from large PDF documents. Traditional keyword search fails to capture context and meaning, making information retrieval inefficient.

💡 Solution

This application uses a Retrieval-Augmented Generation (RAG) approach to:

Process PDF documents

Retrieve the most relevant content using semantic search

Generate accurate answers using a Large Language Model (LLM)

The system combines document retrieval with generative AI to provide reliable, context-aware responses.

## Features ⭐
* Process PDF files and extract information for answering questions.
* Maintain chat history and provide detailed explanations.
* Generate responses using a Conversational Retrieval Chain.
* Display specific pages of PDF files according to the answer.

## Prerequisites 📋
Before running the ChatBot, ensure that you have the required dependencies installed. You can install them using the following command:
```
pip install -r requirements.txt
```

## Configuration ⚙️
The ChatBot uses a configuration file (config.yaml) to specify Hugging Face model and embeddings details. Make sure to update the configuration file with the appropriate values if you wanted to try another model or embeddings.

## Usage 📚
1. Upload a PDF file using the "📁 Upload PDF" button.
2. Enter your questions in the text box.
3. Click the "Send" button to submit your question.
4. View the chat history and responses in the interface.
![image](https://github.com/Niez-Gharbi/PDF-RAG-with-Llama2-and-Gradio/assets/57814219/77b76c05-86fe-4020-8c7a-cf3d7402dcfd)

## Running Locally 💻
To run the PDF Interaction ChatBot, execute the following command:

```
cd src
python app.py
```

## License
This project is licensed under the [Apache License 2.0](https://github.com/Niez-Gharbi/PDF-RAG-with-Llama2-and-Gradio/blob/main/LICENSE).
