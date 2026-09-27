# Exam Question Generator

An NLP-based web application that automatically generates examination questions from syllabus text or PDF files.

## Features
- Upload syllabus PDF
- Enter syllabus text
- NLP preprocessing
- TF-IDF keyword extraction
- MCQ, Fill in the Blanks and Short Answer questions
- Easy, Medium and Hard difficulty
- Download generated questions as PDF

## Technologies
Python, Flask, NLTK, Scikit-learn, TF-IDF, PyPDF2, FPDF, HTML, CSS, JavaScript and Bootstrap.

## Installation

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

Open:

http://127.0.0.1:5000

## Project Structure

```text
exam-question-generator/
├── app.py
├── requirements.txt
├── README.md
├── templates/
│   └── index.html
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── script.js
└── uploads/
```
