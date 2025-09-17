# 📝 RAG Q&A With PDF + Chat History

This project is a **Conversational RAG (Retrieval-Augmented Generation)** app built with **Streamlit**.  
It allows you to **upload PDFs** and chat with their content while maintaining **chat history**.

---

## 🚀 Features
- 📂 Upload multiple PDF files.
- 🔍 Retrieve context-aware answers using **LangChain + Chroma Vector DB**.
- 🤖 Uses **Groq LLM (Gemma2-9b-It)** for natural conversation.
- 🧠 Maintains **chat history across sessions**.
- ✂️ Text is split & embedded using **HuggingFace embeddings**.

---

## 🛠️ Tech Stack
- [Streamlit](https://streamlit.io/) – UI framework  
- [LangChain](https://www.langchain.com/) – Conversational AI framework  
- [Chroma](https://www.trychroma.com/) – Vector database  
- [HuggingFace Embeddings](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)  
- [Groq API](https://groq.com/) – LLM inference  

---

## 📂 Project Structure
5.RAG_QA_Conversation/
│── app.py # Main Streamlit application
│── temp.pdf # Sample PDF for testing
│── requirements.txt
│── README.md # Project documentation


---

## ⚙️ Setup Instructions

1️⃣ Clone the repo:
```bash
git clone https://github.com/your-username/rag-qa-pdf.git
cd rag-qa-pdf
2️⃣ Create & activate virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate    # Mac/Linux
venv\Scripts\activate       # Windows
3️⃣ Install dependencies:

bash
Copy code
pip install -r requirements.txt
4️⃣ Create a .env file:

env
Copy code
HF_TOKEN=your_huggingface_token
5️⃣ Run the app:

streamlit run app.py
```
## 🔑 API Keys Required
Groq API Key → Enter inside the Streamlit UI when prompted.

HuggingFace Token → Stored in .env file.

## 📦 Requirements
Here are the dependencies used in this project:

streamlit
langchain
langchain-community
langchain-core
langchain-chroma
langchain-groq
langchain-huggingface
langchain-text-splitters
chromadb
huggingface-hub
python-dotenv
pypdf
 
