# Multi-PDF-s 📚 ChatApp AI Agent 🤖

**Meet Multi-PDF Chat AI App!** 🚀  
Chat seamlessly with multiple PDFs using **LangChain**, **Google Gemini Pro**, and **FAISS Vector DB**, deployed effortlessly with **Streamlit**. Get **instant, accurate responses** powered by the robust Google Gemini open-source language model. 📚💬  
**Transform your PDF experience today!** 🔥✨  

---

## 📝 Description

The **Multi-PDF's Chat Agent** is a Streamlit-based web application designed for interactive conversations with a chatbot. Upload multiple PDF documents, extract text information, train the chatbot with the extracted content, and engage in real-time conversations.  

---

## 📢 Demo App with Streamlit Cloud (Visualize Only)

[![Launch App](https://img.shields.io/badge/Launch_Streamlit_App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)]()

---

## 🎯 How It Works

![MultiPDF Chat App Diagram](img/Architecture.jpg)

### Steps for Response Generation:

1. **PDF Loading**: Extract text content from uploaded PDF documents.
2. **Text Chunking**: Divide extracted text into manageable chunks for processing.
3. **Language Model Integration**: Generate vector representations (embeddings) of text chunks using LLMs.
4. **Similarity Matching**: Compare your question with text chunks to find the most relevant ones.
5. **Response Generation**: Provide an accurate, contextually relevant response based on the identified chunks.

![Demo Output](img/LLMframework.jpg)

---

## 🌟 Key Features

- **Adaptive Chunking**: Dynamically adjusts window size and position using sliding window techniques, optimizing data retrieval for fine and coarse contexts.  
- **Multi-Document QA**: Supports single and multi-hop queries across multiple documents.  
- **File Compatibility**: Handles both PDF and TXT files seamlessly.  
- **LLM Model Compatibility**: Compatible with Google Gemini Pro, OpenAI GPT-3, Anthropic Claude, Llama2, and other open-source LLMs.

---

## 🌟 Requirements

### Core Libraries
- **[Streamlit](https://streamlit.io/)**: Interactive Python web app framework.  
- **[google-generativeai](https://pypi.org/project/google-generativeai/)**: Powers generative AI capabilities for chatbots.  
- **[python-dotenv](https://pypi.org/project/python-dotenv/)**: For managing environment variables securely.  
- **[LangChain](https://langchain.readthedocs.io/)**: Tools for conversational retrieval, embeddings, and vector storage.  
- **[PyPDF2](https://pypi.org/project/PyPDF2/)**: PDF extraction and manipulation.  
- **[FAISS-CPU](https://pypi.org/project/faiss-cpu/)**: Efficient similarity search for dense vectors.  
- **[LangChain Google GENAI](https://pypi.org/project/langchain-google-genai/)**: LangChain integration with Google's generative AI SDK.

---

## ▶️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/alimdsaif3/Multi-PDFs_ChatApp_AI-Agent.git

---


