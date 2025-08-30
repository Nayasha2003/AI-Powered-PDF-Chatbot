# 🦙📄 AI PDF Chatbot

An 🧠 AI-powered PDF Chatbot 🤖 that allows you to 📂 upload any PDF and 💬 chat with it in natural language.
Built with 🦙 Llama 3.1, ⚡ Groq API, 🔗 LangChain, 📊 FAISS, and 🌐 Streamlit using a 📖 Retrieval-Augmented Generation (RAG) approach.

---

📸 Screenshots

![Upload PDF](https://raw.githubusercontent.com/Nayasha2003/AI-Powered-PDF-Chatbot/7f17e85c179bb0d82e0b9b3d2be8809a13b8d8ca/1.jpg)

### Chat with Document
![Chat with Document](https://raw.githubusercontent.com/Nayasha2003/AI-Powered-PDF-Chatbot/7f17e85c179bb0d82e0b9b3d2be8809a13b8d8ca/2.jpg)



## ✨ Features
- 📂 Upload and process **PDF documents**
- 💬 **Chat** with your PDF in real-time
- ⚡ Powered by **Groq’s Llama 3.1-70B** (ultra-fast inference)
- 🔎 Uses **FAISS vector database** for semantic search
- 🧠 **RAG (Retrieval-Augmented Generation)** for accurate context-based answers
- 🌐 **Streamlit UI** for an interactive chat interface
- 🔒 Secure **API key management** with `.env`

---

## 🛠️ Tech Stack
- **LLM**: Llama 3.1 (via Groq API)  
- **Frameworks**: LangChain, Streamlit  
- **Vector DB**: FAISS  
- **Embeddings**: HuggingFace Sentence Transformers  
- **Others**: Python, dotenv, PyPDF  

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Nayasha2003/ai-pdf-chatbot.git
cd ai-pdf-chatbot
2️⃣ Create Virtual Environment

python -m venv .venv
.\.venv\Scripts\Activate   # On Windows PowerShell
# or
source .venv/bin/activate  # On Mac/Linux
3️⃣ Install Dependencies

pip install --upgrade pip
pip install -r requirements.txt
4️⃣ Setup Environment Variables
Create a .env file in the project root:

env

GROQ_API_KEY=your_groq_api_key_here
5️⃣ Run the App

streamlit run main.py
Your app will open in the browser at http://localhost:8501.


Chat with Document

📂 Project Structure
bash
Copy code
├── main.py              # Streamlit app
├── requirements.txt     # Dependencies
├── .env                 # API keys (not pushed to GitHub)
└── README.md            # Project documentation
🎯 Use Cases
📚 Students: Chat with textbooks and lecture notes

📊 Professionals: Extract key insights from research papers or reports

⚖️ Legal Teams: Summarize long case files quickly

🏢 Businesses: Query contracts, manuals, or policy documents
