# 📄 InvoiceIntel – Smart Invoice Parsing with AI

<details>
<summary>📽️ Watch Demo</summary>

[▶️ Click to Watch Demo](https://user-images.githubusercontent.com/76186054/214171508-8ef2e3c1-f3fe-46f7-ad6d-ba3677c762f1.mp4)

</details>

---

## 🚀 Overview

**InvoiceIntel** is an AI-powered web application built with Flask that automatically extracts key information from invoices, receipts, and other business documents using OCR and pre-trained NLP models.

This project demonstrates the power of combining document image processing with natural language understanding — transforming complex invoices into structured, searchable data.

> ⚠️ This is a learning-focused, open-source project. Use for experimentation or prototyping only — not production.

---

## 🧠 Key Features

- ✅ Upload invoices in PDF format (single or multi-page)
- 📷 Converts PDFs to high-resolution images using `pdf2image`
- 🔍 Extracts structured data (date, invoice number, amount, etc.) using:
  - Tesseract OCR
  - Layout-aware Document Question Answering model: [`impira/layoutlm-document-qa`](https://huggingface.co/impira/layoutlm-document-qa)
- 🌐 Clean and user-friendly Flask-based UI
- 💡 Explore how deep learning can help automate repetitive business tasks

---

## 🔧 Tech Stack

| Area              | Tool / Framework                            |
|-------------------|---------------------------------------------|
| Backend           | Python, Flask                               |
| OCR               | Tesseract OCR                               |
| PDF Processing    | pdf2image, Pillow                           |
| NLP Model         | LayoutLM Document QA via Hugging Face Hub   |
| Frontend          | HTML, CSS, Bootstrap                        |
| Others            | Waitress (for production-ready hosting)     |

---

## 📦 Installation Guide

### ✅ Requirements

- Python 3.9+
- pip
- Git
- ~5 GB of free disk space

### 🔧 Setup Instructions

```bash
git clone https://github.com/sumeetpatekar/InvoiceIntel.git
cd InvoiceIntel
pip install -r requirements.txt
python main.py
