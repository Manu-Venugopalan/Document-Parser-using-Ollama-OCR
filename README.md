# Document-Parser-using-Ollama-OCR

## Document-Parser-using-Ollama-OCR

![Made with Python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)
![OCR](https://img.shields.io/badge/OCR-Ollama%20Vision%20OCR-blue)
![Document Parsing](https://img.shields.io/badge/Task-Document%20Parsing-lightgrey)
![CLI Tool](https://img.shields.io/badge/Interface-CLI-green)
![Modular](https://img.shields.io/badge/Design-Modular-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)


This project leverages **Ollama OCR** to extract structured data from input documents (PDFs, images, scanned files, etc.). It's designed to automate data extraction workflows by converting unstructured visual content into usable digital information.

---

### 🔍 Features
- 📄 **OCR Extraction**: Uses Ollama OCR to read and digitize text from image-based documents.
- 🧠 **Information Parsing**: Automatically extracts relevant fields like names, dates, totals, etc.
- ⚙️ **Modular Design**: Easy to integrate with additional AI/NLP pipelines for semantic understanding.
- 🖥️ **CLI Demo**: A `demo.py` script is included to test and visualize the extraction process.

---

### 💼 Use Cases
- Invoice data extraction  
- Receipt scanning and summarization  
- Form digitization (e.g., insurance, healthcare, finance)  
- ID document parsing

---

### 🚀 Getting Started
1. Install dependencies from `ollama-ocr`.
2. We need to install Ollama plugin or tool. After that just do `ollama pull granite3.2-vision`.
3. Run `demo.py` and provide an input file (PDF/image)
4. View the extracted details in the console or output file

---

