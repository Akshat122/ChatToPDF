# PDF Chatbot using Orca Mini 3B

This project is a chatbot designed to read and interact with PDF documents Offline. It leverages the **Ollama Orca Mini 3B model** to extract information from PDF files and provide answers to user queries. The project is implemented in a Jupyter Notebook with supporting functions in an external Python file.

## Features
- Parses and reads PDF documents.
- Provides answers to user queries based on the PDF content using the Orca Mini 3B model.
- Handles multi-page documents efficiently.

## Prerequisites

- Python 3.8+ (recommend using a virtual environment)
- Jupyter Notebook
- Ollama for the Orca Mini 3B model

## Setup Instructions

### 1. Clone the repository

First, clone the repository to your local machine:

```bash
git clone git@github.com:Akshat122/ChatToPDF.git
```

## Create and activate a virtual environment

To avoid dependency conflicts, it's recommended to use a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

## Install required dependencies
Install the necessary Python packages using the `requirements.txt` file:
```bash
pip install -r requirements.txt
```


## Install Ollama
Ollama is required to run the Orca Mini 3B model. Install it using the following command:

```bash
curl https://ollama.ai/install.sh | sh
```
After installation, verify that Ollama is working by running the following command:

```bash
ollama run orca-mini
```

If you are using WSL (Windows Subsystem for Linux), you'll need to run an additional command in a separate terminal to start the server:

```bash
ollama serve
```

## Run the Jupyter Notebook

Once everything is set up, start the Jupyter Notebook server:
```bash
jupyter notebook
```
Open the `ChatToPDF.ipynb` file in your browser, which is the main notebook for interacting with the chatbot. Follow the instructions within the notebook to upload PDFs and ask questions.


# File Descriptions
- ChatToPDF.ipynb: This is the main Jupyter Notebook where you can upload PDF documents and interact with the chatbot.
- lang_funcs.py: Contains supporting functions for language processing that are imported into the notebook.
- requirements.txt: A list of Python dependencies required for the project















