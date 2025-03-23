# 🔍 AI-Powered Document Search with LLM, LangChain, Cassandra & Astra DB (Vector Database)

This project demonstrates how to use **Generative AI** with **LLMs (Large Language Models)**, **LangChain**, **Cassandra**, and **Astra DB (Vector Database)** for efficient document searching and retrieval. It integrates **OpenAI embeddings**, **Astra DB (built on Cassandra) vector storage**, and **LangChain** to build a scalable AI-powered knowledge retrieval system.

---

## 🚀 Features
- **📄 PDF Querying**: Extracts information from PDFs using `pdfquery` and `PyMuPDF`
- **🧠 AI Embeddings**: Uses OpenAI’s `text-embedding-ada-002` model for vector embeddings
- **📊 Vector Storage**: Stores embeddings in **Astra DB (Cassandra Vector Database)**
- **🔍 Semantic Search**: Queries documents intelligently using **LangChain & LLMs**
- **🌐 Cloud Deployment**: Can be extended to deploy on **AWS/GCP**

---

## 🛠️ Technologies Used
- **Python** 🐍
- **LangChain** (AI-powered document querying)
- **LLMs (Large Language Models)**
- **Cassandra & Astra DB (Vector Database)**
- **OpenAI API** (Embeddings)
- **pdfquery** / **PyMuPDF** (PDF parsing)
- **Jupyter Notebook** (Execution)

---

## 📂 Project Structure
```
📂 AI-Document-Search-LLM-LangChain-Cassandra-AstraDB
│── 📄 README.md   # Project documentation
│── 📜 requirements.txt  # Dependencies
│── 📑 PDFQuery_LangChain.ipynb  # Main Jupyter Notebook
│── 📂 data  # Folder for PDFs
└── 📂 embeddings  # Folder for stored embeddings
```

---

## 🔧 Setup Instructions

### **1️⃣ Install Dependencies**
Ensure you have Python 3.8+ installed, then install required libraries:
```bash
pip install -r requirements.txt
```

### **2️⃣ Set Up Astra DB**
1. **Create an Astra DB instance**: [Astra DB](https://www.datastax.com/products/datastax-astra)
2. **Download the Secure Connect Bundle** and place it in the project folder.
3. Update the `SECURE_CONNECT_PATH` in the notebook.

### **3️⃣ Set Up OpenAI API**
- Get an **API key** from [OpenAI](https://platform.openai.com/)
- Set it in the notebook:
  ```python
  import openai
  openai.api_key = "your_openai_api_key"
  ```

### **4️⃣ Run the Jupyter Notebook**
Launch the notebook and execute each cell:
```bash
jupyter notebook
```

---

## 📌 How It Works
1. **Extracts text** from PDFs
2. **Generates vector embeddings** using OpenAI
3. **Stores embeddings in Astra DB (Cassandra Vector Database)**
4. **Queries documents using LangChain & LLMs**
5. **Retrieves relevant answers** based on vector similarity

---

## 🎯 Future Improvements
- Deploy as a **web app** (Streamlit/FastAPI)
- Integrate **RAG (Retrieval-Augmented Generation)** for ChatGPT-like answers
- Improve indexing with **FAISS** or **Pinecone**

---

## 👤 Author
- **Mansi** (Data Science Enthusiast 🚀)

---

## 📝 License
This project is for educational purposes only.

---

💡 *Have any suggestions? Feel free to contribute!* 🚀

