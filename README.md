# Ask from PDFs using Gemini

## Description

This project allows users to ask questions about the content of PDF documents. By using Google Generative AI and FAISS for managing text data, the application lets you upload PDF files, process their content, and get answers to your questions based on the information in the PDFs. If the answer isn’t available in the PDF, the app will let you know politely.

## Features

- Upload and process multiple PDF files.
- Extract text from PDFs.
- Break text into smaller chunks for better handling.
- Generate text embeddings using Google Generative AI.
- Store and retrieve text embeddings with FAISS.
- Ask questions about the PDFs and receive detailed answers.
- Inform users when information is not available.

## Installation

### Prerequisites

- Python 3.10+
- pip

### Steps

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/ask-from-pdf-gemini.git
    cd ask-from-pdf-gemini
    ```

2. **Create a virtual environment**:

    ```bash
    python -m venv myenv
    source myenv/bin/activate  # On Windows: myenv\Scripts\activate
    ```

3. **Install dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

4. **Set up environment variables**:

    Create a `.env` file in the project directory and add your Google API key:

    ```plaintext
    GOOGLE_API_KEY=your_google_api_key
    ```

5. **Run the application**:

    ```bash
    streamlit run app.py
    ```

## Usage

1. **Upload PDF Files**: Use the sidebar to upload one or more PDF files.
2. **Process Files**: Click "Submit & Process" to analyze and store the text from the PDFs.
3. **Ask Questions**: Type your question in the input field at the top of the page.
4. **View Answers**: The app will show answers based on the content of the uploaded PDFs.

## Example

1. Upload your PDF files using the sidebar.
2. Click "Submit & Process" to start processing.
3. Type questions about the content of the PDFs.
4. See the answers displayed on the page.

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [PyPDF2](https://pypi.org/project/PyPDF2/)
- [LangChain](https://www.langchain.com/)
- [FAISS](https://faiss.ai/)
- [Google Generative AI](https://ai.google/tools/)

