
# LegalEase: Your AI-Powered Legal Assistant

LegalEase simplifies legal document analysis using AI. It helps identify document types, extract key information, simplify legal jargon, and summarize content, making legal processes more accessible. This project was created for the GenAI Hackathon.

---

## Features

1. **Document Identification**  
   - Automatically determines the type of legal document (e.g., contract, agreement, affidavit).  

2. **Key Information Extraction**  
   - Extracts critical details like dates, organizations, names, and locations (supports cities in Maharashtra).  

3. **Plain Language Simplification**  
   - Converts complex legal language into plain English for better comprehension.  

4. **Summarization**  
   - Provides concise summaries of lengthy legal documents.  

5. **Multilingual Support**  
   - Handles English, Marathi, Hindi, and Tamil. Translates non-English text to English for processing.  

6. **Chatbot (Optional)**  
   - A basic chatbot for interaction using keyword matching.  
   - Advanced chatbot capabilities using the **Google Gemini API** (if enabled).  

---

## Technical Details

- **Backend Framework**: Flask (Python)  
- **OCR**: Tesseract OCR  
- **PDF Processing**: PyPDF2, pdf2image  
- **Translation**: Deep Translator (Google Translate)  
- **Summarization**: Sumy  
- **NLP**: spaCy, NLTK, WordNet  
- **Paraphrasing**: Transformers (T5-small model)  
- **Chatbot (Advanced)**: Google Gemini API (optional)  
- **Frontend**: HTML, CSS, JavaScript  

---

## Installation

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/nikhil8424/GenAi-Hackathon.git
   cd GenAi-Hackathon
   ```

2. **Set Up a Virtual Environment** (Recommended)  
   - **Windows**:  
     ```bash
     python3 -m venv venv
     venv\Scripts\activate
     ```  
   - **macOS/Linux**:  
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```

3. **Install Required Libraries**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Install Tesseract OCR**  
   - Download and install Tesseract OCR for your platform.  
   - Update the `pytesseract.pytesseract.tesseract_cmd` path in `app.py`.

5. **Set Up Google Gemini API Key (Optional)**  
   - If using the advanced chatbot feature, configure the Gemini API key as an environment variable.  

---

## Usage

1. **Upload a Document**  
   - Upload a PDF, PNG, or JPG file.  

2. **Choose Document Language**  
   - Select the language of the document (e.g., English, Marathi).  

3. **Select Functionality**  
   - Choose from features like document identification, key point extraction, simplification, or summarization.  

4. **View Results**  
   - Review the processed output.  

5. **Use the Chatbot (Optional)**  
   - Interact with the chatbot for queries.  

---

## Future Enhancements

- Improved UI/UX  
- Enhanced chatbot capabilities  
- Support for more languages  
- Integration with advanced legal AI models  

---

## Contributing

Contributions are welcome! Please submit a pull request or report issues.

---
## TO RUN CODE
download zip -> extract to a directory
open cmd 
move to that directory
run the following command : 
python app.py
