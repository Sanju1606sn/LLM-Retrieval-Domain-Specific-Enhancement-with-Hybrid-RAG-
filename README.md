
---

## 2️⃣ LLM-RAG

```markdown
# 🔍 LLM-RAG: Enhancing LLM Accuracy with Retrieval-Augmented Generation

This project explores **Retrieval-Augmented Generation (RAG)** to mitigate **LLM hallucinations** and improve accuracy for domain-specific queries.

## 🚀 Features
- Combines **retrievers** (BM25, Bi-Encoder, Cross-Encoder) with **LLMs (GPT, LLaMA)**.
- Implements **LoRA** and **QLoRA** fine-tuning for parameter-efficient adaptation.
- Cross-encoder retrievers demonstrated **best retrieval performance**.
- Achieved **higher exact-match accuracy** compared to standalone LLMs.

## 🛠️ Tech Stack
- Python, Hugging Face Transformers  
- GPT, LLaMA models  
- BM25, Sentence-BERT, Cross-Encoder retrievers  
- LoRA / QLoRA fine-tuning  

## 📂 Dataset
- Domain-specific QA dataset (course assignment: CS626, IIT Bombay).  

## 📊 Results
- **Cross-encoder > Bi-encoder > BM25** in retrieval accuracy.  
- **Fine-tuned LLM with RAG** outperformed both standalone fine-tuned LLMs and vanilla LLM+RAG.

## ▶️ Usage
```bash
git clone https://github.com/TrivikramUmanath/LLM-RAG.git
cd LLM-RAG
jupyter notebook
