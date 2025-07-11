# 🥕 Nutrition Planner Assistant

An AI-powered assistant that answers nutrition-related questions from uploaded product manuals and documents. Built using OpenAI's GPT via OpenRouter, Qdrant vector DB, and Streamlit, it combines the power of document retrieval with friendly, emoji-rich AI responses and voice output.

---

## 🌟 Features

- 🔍 **Document Search**: Upload product manuals (PDF, DOCX, XLSX, etc.) and query them using natural language.
- 🧠 **AI Assistant**: NutriAdvisor provides smart, friendly nutrition advice.
- 🖼️ **Image Context**: Displays related images from the product manual when relevant.
- 🔊 **Voice Output**: Converts answers to speech with adjustable rate and voice gender.
- 🌱 **Personalized Suggestions**: Offers food recommendations based on dietary preferences and seasons.

---

## 🚀 Tech Stack

| Component           | Tech                                |
|---------------------|-------------------------------------|
| Frontend UI         | Streamlit                           |
| Backend Logic       | Python                              |
| Vector DB           | Qdrant (BM25 + BGE Embeddings)      |
| AI Model            | GPT-4o-mini via OpenRouter          |
| Document Parsing    | PyMuPDF (fitz), docling             |
| Text-to-Speech      | pyttsx3                             |
| Image Processing    | base64, PIL                         |

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/nutrition-planner.git
cd nutrition-planner
