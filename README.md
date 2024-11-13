## RAG based Chatbot
I have used Retrieval augmented generation via `langchain` to create a chatbot that answers questions related to a pdf when given to it. The app has been hosted on streamlit at [pdf-chatbot-owais](https://pdf-chatbot-owais.streamlit.app/)

Here’s a more concise `README.md` for your RAG-Chatbot project:

---

# RAG-Chatbot

This repository hosts a Retrieval-Augmented Generation (RAG) based question-answering chatbot designed to answer questions related to files uploaded by the user. The app is deployed on Streamlit, providing an interactive interface for users to upload files and receive answers.

## Overview

The RAG-Chatbot uses LangChain to implement a retrieval-based system that augments language generation with file-specific context. The app is tailored for scenarios where users need precise answers from specific documents, making it ideal for document review and information extraction.

## Features

- **RAG Architecture**: Combines retrieval and generation to answer questions accurately.
- **LangChain Integration**: Leverages LangChain’s capabilities to process and retrieve relevant data.
- **File-Specific Q&A**: Accepts PDFs or other documents as input, enabling precise responses.
- **Streamlit Interface**: Provides an easy-to-use web interface for seamless interaction.

## Repository Structure

- **constants.py**: Defines constants used across the application.
- **mindcase_submission.ipynb**: A Jupyter notebook for submission and testing.
- **pdf_qa.py**: Contains core functions for processing PDF files and performing QA.
- **pipeline_qa.yaml**: YAML configuration file for defining the RAG pipeline.
- **requirements.txt**: Lists the required dependencies.
- **run_qa.sh**: Script to launch the application.
- **streamlit_app_blog.py**: Streamlit app file for deployment on Streamlit.

## Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/RAG-Chatbot.git
   cd RAG-Chatbot
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   ./run_qa.sh
   ```

### Usage

Once deployed, visit the Streamlit app URL to upload files and interact with the chatbot. The chatbot will process the uploaded file and provide relevant answers based on the content.

## Deployment on Streamlit

To deploy on Streamlit, follow the instructions in `streamlit_app_blog.py`. Ensure you configure any necessary API keys and environment variables. Currently my version is deployed at this URL: [pdf-chatbot-owais](https://pdf-chatbot-owais.streamlit.app/)

## License

This project is licensed under the MIT License.
