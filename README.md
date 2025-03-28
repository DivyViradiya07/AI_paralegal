# ⚖️ AI Paralegal

AI Paralegal is an AI-powered legal assistant that helps analyze legal documents, generate legal drafts, and answer legal queries. It leverages **Retrieval-Augmented Generation (RAG)** for intelligent document processing and legal research.

---

## 🚀 Features

- 📄 **Legal Document Generation**: Drafts writ petitions, affidavits, patent applications, and more.
- 🤖 **AI-Powered Chatbot**: Answers legal queries based on uploaded case files.
- 📂 **PDF Processing**: Extracts and processes text from legal documents.
- 🔍 **Vector Search**: Uses FAISS for efficient legal document retrieval.
- 🎨 **Streamlit Web Interface**: Provides an interactive UI for easy use.

---

## 🛠️ Tech Stack

- **Python** 🐍
- **LangChain** 🔗 (Document processing)
- **FAISS** 🔍 (Vector search)
- **Google Generative AI Embeddings** 🤖
- **Groq API** ⚡ (LLM-powered legal document drafting)
- **Streamlit** 🎨 (UI)
- **PyPDF** 📑 (PDF Handling)

---

## 📂 Project Structure
```
AI_paralegal/
├── .env                   # Environment configuration file
├── AI_paralegal.py        # Main script for the AI Paralegal application
├── doc_draft.py           # Module for document drafting functionalities
├── rag_chatbot.py         # Module for the Retrieval-Augmented Generation chatbot
├── requirements.txt       # List of required Python packages
├── Downloads/             # Directory for downloaded files
├── SampleDocuments/       # Directory containing sample legal documents
│   ├── Affidavit.pdf      # Sample affidavit document
│   └── Writ_petition.pdf  # Sample writ petition document
└── __pycache__/           # Directory for compiled Python files
    ├── doc_draft.cpython-312.pyc
    └── rag_chatbot.cpython-312.pyc

```

## 📦 Installation Guide

```sh
### 1️⃣ Clone the Repository  

git clone https://github.com/DivyViradiya07/AI_paralegal.git
cd AI_paralegal

2️⃣ Create a Virtual Environment
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Set Up Environment Variables
Create a .env file in the project root and add:
GOOGLE_API_KEY=your_google_api_key
GROQ_API_KEY=your_groq_api_key

🏃‍♂️ Running the Application
streamlit run AI_paralegal.py
