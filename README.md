# LegalEase: Your AI-Powered Legal Assistant

LegalEase simplifies legal document analysis using AI.  It identifies document types, extracts key information, simplifies legal jargon, and summarizes text. This project was created for a GenAI Hackathon.

## Features

* **Document Identification:**  Determines the type of legal document.
* **Key Information Extraction:** Extracts dates, organizations, locations (Maharashtra cities), and names.
* **Plain Language Simplification:**  Converts complex legal text into plain English.
* **Summarization:** Provides concise document summaries.
* **Multilingual Support:** Handles English, Marathi, Hindi, and Tamil, translating to English for processing.
* **Chatbot:**  Basic chatbot using keyword matching or (optionally) Google Gemini for advanced interactions.

## Technical Details

* **Framework:** Flask (Python)
* **OCR:** Tesseract OCR
* **PDF Processing:** PyPDF2, pdf2image
* **Translation:** Deep Translator (Google Translate)
* **Summarization:** Sumy
* **NLP:** spaCy, NLTK, WordNet
* **Paraphrasing:** Transformers (T5-small)
* **Chatbot (Advanced):** Google Gemini API (optional)
* **Frontend:** HTML, CSS, JavaScript

## Installation

1. **Clone:** `git clone https://github.com/nikhil8424/GenAi-Hackathon.git`
2. **Navigate:** `cd GenAi-Hackathon`
3. **Virtual Environment (Recommended):**
   ```bash
   python3 -m venv venv
   venv\Scripts\activate  # Windows
   source venv/bin/activate  # macOS/Linux
Use code with caution.
Markdown
Install: pip install -r requirements.txt (Create requirements.txt with dependencies - see below)

Tesseract OCR: Download and install. Set pytesseract.pytesseract.tesseract_cmd in app.py correctly.

Gemini API Key (Optional): Set API key in app.py (use environment variables in production).

Requirements.txt Example
flask
PyPDF2
pdf2image
pillow
pytesseract
deep-translator
sumy
spacy
nltk
transformers
google-generativeai  # If using Gemini
Use code with caution.
Usage
Upload a document (PDF, PNG, JPG).

Select the document's language.

Click "Upload".

Choose a functionality (Identify, Key Points, etc.).

View results.

Use the chatbot (optional).

Future Enhancements
Improved UI/UX

Enhanced chatbot

More language support

Advanced legal AI integration

Contributing
Contributions welcome! Submit pull requests.

License
[Specify your license here. E.g., MIT License]

This version is more concise while retaining essential information.  Remember to replace placeholders like "[Specify your license here]" with the actual license you are using.
