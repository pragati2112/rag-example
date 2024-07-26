# Easy RAG 

### This is a basic RAG example with help of Langchain and Ollama. Using Streamlit (It turns data scripts into shareable web apps in minutes.)
It is a Chat-pdf (simple question-answer chat), upload a pdf document and ask questions. Model will answer the questions in context of uploaded document.

## Setup
    - Clone the repository
    - Create and activate virtualenv (I am using Python 3.11.9)
    - pip install -r requirements.txt
    - Download Ollama

## Run
```sh
ollama pull mistral
ollama serve
streamlit run main.py
```

Streamlit server is serving on http://localhost:8501
