# GenAI_Project

## 📁 Project 2: AI Handbook Assistant using RAG
This project demonstrates a simple Retrieval-Augmented Generation (RAG) pipeline that answers user queries based on a set of handbooks.

### 🧠 Features
- Loads multiple documents (Python Basics, Git Commands, etc.)
- Splits text into small searchable chunks
- Creates embeddings using Sentence Transformers
- Retrieves the most relevant chunks for a given query
- Generates simulated AI responses grounded in the documents

### 🚀 How to Run
1. Open `rag_assistant.ipynb` in Google Colab.
2. Upload your `.txt` handbooks in the same environment.
3. Run all cells sequentially.

### 🧩 Dependencies
- Python 3.x  
- sentence-transformers  
- numpy

### Folder structure:
<pre>
GenAI_Project/
├── Project2_RAG/
│ ├── rag_assistant.ipynb # Main notebook (RAG pipeline)
│ ├── rag_assistant_report.pdf # 1-page report explaining logic & learnings
│ └── handbook_texts/ # Text documents used for retrieval
│ ├── python_basics.txt
│ ├── git_commands.txt
│ └── general_notes.txt
└── README.md # Project overview and instructions </pre>

### 🧾 Output
The assistant retrieves relevant document sections and produces grounded answers for user queries such as:
- "What is Git used for?"
- "How do I define a function in Python?"

### 📄 Author
**Nishant Roy**
