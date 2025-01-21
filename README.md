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
   git clone [https://github.com/GURPREETKAURJETHRA/Multi-PDFs_ChatApp_AI-Agent.git](https://github.com/alimdsaif3/Multi-PDFs_ChatApp_AI-Agent-main.git)


Install the required Python packages:

`pip install -r requirements.txt`

Set up your Google API key from `https://makersuite.google.com/app/apikey` by creating a .env file in the root directory of the project with the following contents:

`GOOGLE_API_KEY =<your-api-key-here>`

Run the Streamlit app:

`streamlit run app.py`

---
## 💡Usage

To use the Multi-PDF-s 📚ChatApp AI Agent 🤖, U can have glimpse of look by clicking on this link : [Launch App On Streamlit](https://multi-pdfschatappai-agent.streamlit.app/). To run app, fork app and follow the below steps to start using it. Use the sidebar to upload PDF files and train the chatbot. Once trained, you can have conversations with the chatbot by entering questions in the text input field.

In case You want to run & implement project on your system then follow these steps:

1. Ensure that you have installed the required dependencies and added the **Google API key to the `.env` file** (MUST).
2. Run the `app.py` file using the Streamlit CLI. Execute the following command:
   ```
   streamlit run app.py
   ```
3. The application will launch in your default web browser, displaying the user interface.
4. Upload multiple PDF documents into the app by following the provided instructions at sidebar. On the sidebar, you'll find an option to upload PDF documents. Click on the "Upload your documents here and click on Process" button and select one or more PDF files. 
5. Don't forget to click on Submit & Process Button.
6. Ask questions in natural language about the loaded PDFs using the chat interface.
7. Chatting with the Documents: After uploading and processing the PDF documents, you can ask questions by typing them in the text input field. Press Enter or click the "Ask" button to submit your question.

The application will use conversational AI to provide responses based on the content of the uploaded documents. The responses will be displayed in the chat interface.

---
## ©️ License 🪪 

Distributed under the MIT License. See `LICENSE` for more information.

---

#### **If you like this LLM Project do drop ⭐ to this repo**
#### Follow me on [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/md-saif-ali-9815a774/) &nbsp; [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/alimdsaif3)

---
#   M u l t i - P D F s _ C h a t A p p _ A I - A g e n t - m a i n 
 
 
