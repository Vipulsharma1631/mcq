An AI-powered **Multiple Choice Question (MCQ) generator** built with the **OpenAI API**.  
It allows users to upload content (PDFs/text), process it, and automatically generate MCQs for testing and assessments.  

## 🚀 Tech Stack

- **Python** – Core language  
- **OpenAI API** – Used for text understanding and MCQ generation  
- **Flask** – Web backend framework  
- **PyPDF / PDFplumber** – For extracting text from PDFs (if used)  
- **HTML, CSS, JS** – Web interface (in `templates/` and `static/`)  

---

## ✨ Features

- 📄 Upload PDFs or text documents as source material  
- 🤖 Generate **Multiple Choice Questions (MCQs)** using the OpenAI API  
- 🎯 Supports custom question count, difficulty levels, and topics  
- 🌐 Web interface for easy interaction  
- 📦 Export MCQs to different formats (JSON, text, or DB-ready)  
- ⚡ Fast and reliable thanks to OpenAI’s GPT models  

---

## 📂 Project Structure

```bash
mcq/
├── app.py              # Flask app entry point
├── requirement.txt     # Dependencies
├── utils/              # Helper functions (parsing, formatting, etc.)
├── templates/          # HTML templates (UI)
├── static/             # CSS/JS frontend assets
├── data/               # Sample input/output files
└── README.md
