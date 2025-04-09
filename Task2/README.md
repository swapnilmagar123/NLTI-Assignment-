# 🎓 CLAT Chatbot Assignment

This is a prototype chatbot that answers **CLAT 2025** related queries using a combination of **rule-based FAQs** and **semantic similarity** using Sentence Transformers.

---

## 🚀 Features

- Answers queries about:
  - Syllabus
  - Cut-offs
  - Exam pattern
  - Section-wise details
  - Books, Eligibility, Reservation
- Built with `Streamlit` for UI
- Uses `sentence-transformers` for semantic matching

---

## 🧠 Architecture

1. **Knowledge Base**: Dictionary of CLAT FAQs
2. **Model**: `all-MiniLM-L6-v2` from Sentence Transformers
3. **Search**: Computes cosine similarity between user query and stored FAQ keys
4. **UI**: Built using Streamlit for rapid deployment

---

## 🔧 Setup Instructions

1. Clone the repo or unzip folder
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
