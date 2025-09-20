# Chat with Multiple PDFs

A Streamlit app that lets you **chat with your PDF documents** using AI. Upload multiple PDFs, and ask questions about their content. Powered by **LangChain**, **FAISS vector store**, and **Perplexity AI**.

---

## Features

- Upload and process multiple PDFs at once.
- Split PDFs into manageable chunks for better AI comprehension.
- Vectorize documents using embeddings for semantic search.
- Interactive conversational interface with memory.
- Streamlit frontend with a clean chat UI.

---

## Setup

### 1. Clone the repo
```bash
git clone https://github.com/yaseenddar/ChatBot.git
cd ChatBot

python -m venv myenv
myenv\Scripts\activate   # Windows
# OR
source myenv/bin/activate  # macOS/Linux
pip install -r requirements.txt

PERPLEXITY_API_KEY=your-perplexity-api-key

streamlit run app.py

Open your browser to the URL Streamlit provides (usually http://localhost:8501).

Upload PDFs via the sidebar and start asking questions.
