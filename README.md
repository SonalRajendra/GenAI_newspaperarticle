# 📰 GenAI Newspaper Article Generator

This project leverages **Generative AI** and **Retrieval-Augmented Generation (RAG)** to create or analyze newspaper-style articles. It uses [LangChain](https://www.langchain.com/) as the core framework and retrieves contextual knowledge dynamically from [Wikipedia](https://www.wikipedia.org/).

## 🚀 Features

- **RAG-powered article generation**: Combines LLMs with real-time context retrieval from Wikipedia
- **LangChain integration**: Modular chains, tools, and agents for structured AI pipelines
- **Hugging Face Transformers support**: Load and run state-of-the-art models
- **Environment configuration** with `.env` support

## 🧠 Technologies Used

- **LangChain** - Framework for building applications with LLMs
- **Retrieval-Augmented Generation (RAG)** - Combines external knowledge retrieval with generation
- **Wikipedia API** - Provides real-time context for informed responses
- **Hugging Face Transformers** - Pretrained language models
- **Python-Dotenv** - Secure environment variable handling

---

## 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/SonalRajendra/GenAI_newspaperarticle.git
cd GenAI_newspaperarticle
```


2. **Install dependencies**
Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

Then install all required packages:
```bash
pip install -r requirements.txt
```


## 🔧 Setup
1. Environment Variables

Create a .env file in the root directory and add your Hugging Face token if needed
```bash
HUGGINGFACEHUB_API_TOKEN=your_token_here
```
2. Run the project



