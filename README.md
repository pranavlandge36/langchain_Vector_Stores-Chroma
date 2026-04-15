# 📦 LangChain Vector Stores

This repository documents my learning and hands-on implementation of **Vector Stores in LangChain**, a core component for building modern AI applications like Retrieval-Augmented Generation (RAG), semantic search, and intelligent chat systems.

---

## 🚀 What I Learned

### 🔹 What are Vector Stores?

Vector stores are systems that store **embeddings (numerical representations of data)** and enable **semantic similarity search**.

Instead of keyword-based matching, they allow us to find information based on **meaning**.

---

### 🔹 Why were Vector Stores introduced?

Traditional databases struggle with:

* ❌ Semantic understanding (meaning-based search)
* ❌ Handling unstructured data like text, PDFs, documents
* ❌ Finding similar content beyond exact keyword matches

Vector stores solve this by:

* ✅ Converting text into embeddings using ML models
* ✅ Storing high-dimensional vectors efficiently
* ✅ Performing fast similarity search (nearest neighbor search)

---

### 🔹 Problem They Solve

Example:

Query: *"Who uses a hammer?"*

* Traditional search → ❌ No exact keyword match
* Vector search → ✅ Matches **Thor** (understands meaning)

👉 This is the foundation of:

* RAG systems
* AI chatbots
* Recommendation engines

---

## 🛠️ Implementation

I implemented a vector store using **Chroma** with LangChain.

### 🔹 Features Implemented

* ✅ Add Documents
* ✅ Similarity Search
* ✅ Similarity Search with Score
* ✅ Metadata Filtering
* ✅ Update Documents
* ✅ Delete Documents
* ✅ View Stored Data

---

## 🧪 Sample Use Case

Stored documents representing different characters and performed:

* Semantic queries like *"green giant"* → Hulk
* Filter-based queries using metadata
* Updating existing entries in the vector store

---

## ⚙️ Tech Stack

* Python
* LangChain
* Chroma Vector Store
* OpenAI Embeddings

---

## 🧠 Vector Store vs Vector Database

| Feature     | Vector Store                                     | Vector Database                             |
| ----------- | ------------------------------------------------ | ------------------------------------------- |
| Definition  | Interface/library to store & retrieve embeddings | Full-fledged database optimized for vectors |
| Example     | LangChain Chroma wrapper                         | Pinecone, Weaviate, Milvus                  |
| Persistence | Optional / local                                 | Built-in persistent storage                 |
| Scalability | Limited                                          | Highly scalable                             |
| Use Case    | Prototyping, local apps                          | Production systems                          |

---

## 📌 Key Takeaways

* Vector stores enable **semantic search**, not keyword search
* They are essential for **LLM-based applications (RAG)**
* Chroma is a great lightweight option for local development
* Managing duplicates and persistence is crucial
* Understanding embeddings is key to building intelligent systems

---

## 🔮 Next Steps

* Build a full **RAG pipeline**
* Integrate with real-world data (PDFs, APIs)
* Experiment with different embedding models
* Deploy a semantic search application

---

Developed as part of my learning journey in **LangChain and AI Engineering**.

---
