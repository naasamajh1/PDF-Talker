
# 📄 PDF-Talker

PDF-Talker is an AI-powered web app that allows users to **upload a PDF file and interact with it using voice or text commands**. It reads, understands, and responds to questions about the uploaded document – like having a smart assistant for your PDFs.

---

## 🚀 Features

- 📤 Upload any PDF file
- 🧠 Extract and understand document content using AI
- 💬 Text-based chat interface
- 🔍 Ask questions and get answers from the document
- ⚡ Fast and lightweight interface

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask (Python)
- **AI/NLP**: LangChain, OpenAI (or Gemini), PyPDF2

---

## 📂 Project Structure

```
PDF-Talker/
│
├── static/               # Static files (CSS, JS)
├── templates/            # HTML templates
├── app.py                # Flask backend
├── .env                  #Your Gemini-API-KEY
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

---

## 🧪 How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/naasamajh1/PDF-Talker.git
cd PDF-Talker
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate      # On Linux/Mac
venv\Scripts\activate         # On Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the App

```bash
python app.py
```

Visit `http://127.0.0.1:5000` in your browser.

---

## 🎯 Usage

1. Upload a PDF file.
2. Type your question.
3. The app will read the PDF, find the relevant answer, and reply (text or audio).
4. Useful for reading long documents, study material, legal papers, etc.

---

## Demo

https://pdf-talks-ai.streamlit.app/

---

## 📌 Future Improvements

- Multi-page memory-aware Q&A
- OCR support for scanned PDFs
- Save/load chat history
- Mobile-friendly interface
- Multilingual support

---

## 🤝 Contributing

Contributions, suggestions, and pull requests are welcome! Please open an issue first to discuss changes.

---

## 📜 License

MIT License

---

## 👤 Author

**Himanshu ([@naasamajh1](https://github.com/naasamajh1))**
