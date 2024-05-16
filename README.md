# lograg - Explainable logs with Llama3
A very small example of a RAG fucntion implementation to provede context about a log file. The log file is provided as input to a LLM which is run locally using Ollama together with langchain framework.


## Install Ollama
    - https://ollama.com/download

## Install your preferred model locally
    - ollama fetch llama3

## Create an virtual environment
    python3 -m venv .venv
    source .venv/bin/activate

## Install requirements
    pip install -r requirements.txt

## Read more about Ollama
    - https://github.com/ollama/ollama

## Read more about the langchain framework
    - https://python.langchain.com/v0.1/docs/get_started/introduction
