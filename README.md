# granite-rag-llamaindex

A **Retrieval-Augmented Generation (RAG)** agent built using **IBM Granite 3**, **LlamaIndex**, and **watsonx.ai**.  
This project demonstrates how to design a retrieval agent that indexes private documents, embeds them, and generates context-aware answers, combining IBM’s LLM capabilities with efficient information retrieval pipelines.

---

## 🚀 Project Overview
This project showcases a document-based question-answering system powered by **IBM Granite 3** and **LlamaIndex**.  
The agent reads private text files, splits them into nodes, embeds the content, and stores it in a vector index for fast semantic search and summarization.

By integrating **LlamaIndex** with **watsonx.ai**, the pipeline delivers:
- Contextual document summarization  
- Fast retrieval of relevant passages  
- Accurate, grounded answers to user queries  

---

## 🧩 Tech Stack
- **LLM Platform:** IBM watsonx.ai  
- **Model:** Granite 3 (8B Instruct)  
- **Framework:** LlamaIndex  
- **Embeddings:** watsonx Embeddings (SLATE model)  
- **Language:** Python  
- **Environment:** Google Colab  

---

## 📂 Project Structure
granite-rag-llamaindex/
├── .gitignore
├── LICENSE
├── README.md
└── src/
└── rag_granite_llamaindex.py


---

## ⚙️ How It Works
1. Load private documents securely (no data uploaded).  
2. Split them into smaller **nodes** using LlamaIndex’s `SentenceSplitter`.  
3. Generate embeddings with **watsonx Embeddings**.  
4. Store embeddings in a **VectorStoreIndex** for efficient retrieval.  
5. Query the model using **Granite 3** via `WatsonxLLM`.  
6. Return grounded, context-aware responses based on document data.  

---

## 🧠 Key Features
- **Private document retrieval & summarization**  
- **Granite 3 integration via watsonx.ai**  
- **RAG pipeline using LlamaIndex**  
- **Customizable embedding & retrieval parameters**

---

## 🔒 Data Privacy
This project is designed for **private and secure document handling**.  
No data or credentials are included in this repository. Replace placeholders with your own watsonx credentials if running locally.

---

## 🪪 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 👩‍💻 Author
**Kavitha Lingarajegowda**  
AI Product Management enthusiast focused on building intelligent, data-driven systems.  
Exploring how LLMs and retrieval architectures can make enterprise data more accessible and actionable.
