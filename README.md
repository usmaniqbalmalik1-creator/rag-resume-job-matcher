# RAG Resume & Job Matcher

An AI application that analyzes a resume against a job description using retrieval and LLM reasoning to produce a structured matching analysis.

## Features
- LLM-powered question answering or analysis
- Context-aware processing
- Streamlit interface
- Environment-based API configuration
- Clear project structure for extension

## Workflow
User Input -> Context / Schema -> LLM -> Validation or Retrieval -> Result

## Project Structure
```text
rag-resume-job-matcher/
├── app.py
├── requirements.txt
└── .env.example
```

## Quick Start
```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
pip install -r requirements.txt
```

Configure the required variables in `.env` using `.env.example`, then run:

```bash
streamlit run app.py
```

## Portfolio Focus
**RAG • LLM Applications • NLP • Resume Analysis • Python**

> Never commit API keys, passwords, or private user/company data.