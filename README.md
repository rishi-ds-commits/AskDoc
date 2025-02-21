# 📄 AskDoc AI-Powered PDF Analyzer 🚀  

An intelligent **PDF analyzer** that extracts key concepts, generates **questions & answers**, and exports them as a CSV file. Built with **Flask, LangChain, Gemini AI, FAISS, and Hugging Face embeddings**.

## ✨ Features
✅ **PDF Processing** – Extracts and splits text from PDFs  
✅ **AI-Powered Q&A** – Generates high-quality questions & answers using Gemini AI  
✅ **Vector Search** – Uses FAISS for efficient retrieval  
✅ **User-Friendly UI** – Simple file upload and CSV export  
✅ **Lightweight & Fast** – Optimized for quick processing  

## 📂 Project Structure
📂 pdf-analyzer-ai/
 ┣ 📂 src/
 ┃ ┣ 📜 helper.py   # AI processing pipeline
 ┃ ┣ 📜 prompt.py   # Custom prompts for Gemini AI
 ┣ 📂 static/
 ┃ ┣ 📂 docs/       # Uploaded PDFs
 ┃ ┣ 📂 output/     # Generated CSV files
 ┣ 📂 templates/
 ┃ ┣ 📜 index.html  # Frontend UI
 ┣ 📜 app.py        # Flask server
 ┣ 📜 requirements.txt  
 ┣ 📜 README.md  
