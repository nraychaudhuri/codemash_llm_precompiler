# LangChain RAG Template project
---
What is RAG?​

[RAG](https://python.langchain.com/docs/use_cases/question_answering/) is a technique for augmenting LLM knowledge with additional, often private or real-time, data.

Large Language Models (LLMs) have knowledge up to a certain training date and can reason on various topics. To handle private or newer data, they need Retrieval Augmented Generation (RAG) to integrate specific, updated information into their prompts.

So far, RAG applications are the most helpful outcome of the AI revolution.

## Tech Stack

- [LangChain](https://www.langchain.com/) is a framework designed to simplify the creation of applications using large language models.
- [OpenAI](https://platform.openai.com/) LLM
- [Chroma](https://www.trychroma.com/) vector database
- Python v3.9.13
---

## Setup Instructions

### Update .env file

Update the .env file with your OPENAI_API_KEY

### Setup a virtual environment

`python3 -m venv env`

### Load virtual environment (Mac)

`source env/bin/activate`

### Install dependencies

`pip install -r requirements.txt`

### Run Hello RAG

`python hello_rag.py`



