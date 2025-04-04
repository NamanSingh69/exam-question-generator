# Exam Question Generator

<div align="center">

![Exam Question Generator Logo](https://via.placeholder.com/150/4a76a8/FFFFFF?text=EQG)

**AI-powered exam question generation system**  
*Create customized exam papers with a few clicks*

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/downloads/)
[![Flask](https://img.shields.io/badge/flask-2.3.3-lightgrey)](https://flask.palletsprojects.com/)
[![Google Gemini](https://img.shields.io/badge/AI-Gemini-green)](https://ai.google.dev/)

</div>

## 📑 Overview

Exam Question Generator is an AI-powered tool that automates the creation of customized exam papers. It analyzes course materials to extract key topics and generates a variety of question types (multiple choice, short answer, essays) at different difficulty levels. Designed for educators, students, and content creators who need to quickly create high-quality assessment materials.

## ✨ Features

- **Multiple Input Formats**: Support for PDFs, text files, JSON, Markdown, and more
- **AI-Powered Analysis**: Automatic extraction of key topics from course materials
- **Diverse Question Types**: Generate MCQs, short answer questions, and essay prompts
- **Customizable Output**: Control difficulty levels, topic selection, and question types
- **Export Options**: Download exam papers as PDF, HTML, or Markdown
- **Answer Keys**: Option to include detailed answer explanations
- **Modern UI**: Intuitive, responsive interface with drag-and-drop functionality

## 🛠️ Technology Stack

- **Backend**: Python, Flask
- **Frontend**: HTML5, CSS3 (Bootstrap), JavaScript
- **AI Integration**: Google Gemini API
- **PDF Processing**: PyPDF2, pdf2image, pdfkit
- **OCR**: pytesseract

## 📋 Prerequisites

- Python 3.8 or higher
- Google API key for Gemini API access
- For PDF functionality:
  - Tesseract OCR (for text extraction from scanned PDFs)
  - wkhtmltopdf (for HTML to PDF conversion)

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/NamanSingh69/exam-question-generator.git
   cd exam-question-generator
   ```

2. **Set up a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set environment variables**
   ```bash
   # Linux/macOS
   export GOOGLE_API_KEY=your_google_api_key
   
   # Windows
   set GOOGLE_API_KEY=your_google_api_key
   ```

5. **Run the setup script**
   ```bash
   python setup.py
   ```

## 📁 Project Structure

```
exam-question-generator/
├── app.py                # Main Flask application
├── setup.py              # Setup script for environment
├── requirements.txt      # Python dependencies
├── uploads/              # Directory for uploaded files
├── temp_outputs/         # Directory for generated files
└── static/               # Static web assets
    ├── index.html        # Main HTML interface
    └── js/
        └── main.js       # Frontend JavaScript
```

## 📝 Usage

1. **Start the application**
   ```bash
   python app.py
   ```

2. **Access the web interface**
   Open your browser and navigate to:
   ```
   http://localhost:5000
   ```

3. **Generate exam questions in 3 easy steps**:
   - **Upload**: Add your course materials and specify the subject
   - **Configure**: Set question types, difficulty levels, and topics
   - **Export**: Review generated questions and download in your preferred format

## ⚙️ Configuration Options

### Question Generation Parameters

| Parameter | Description | Options |
|-----------|-------------|---------|
| Number of Questions | Total questions to generate | 1-50 |
| Difficulty Level | Question complexity | Easy, Medium, Hard, Mixed |
| Question Types | Format of questions | Multiple Choice, Short Answer, Essay |
| Topics | Subject areas to cover | Automatically detected from content |

### Export Settings

- **Format**: PDF, HTML, Markdown
- **Answer Key**: Include or exclude answers and explanations

## 💡 Use Cases

- **Teachers and Professors**: Create exams and quizzes for classes
- **Students**: Generate practice questions for better preparation
- **Educational Platforms**: Automate question bank creation
- **Training Programs**: Develop assessment materials for corporate training
- **Online Courses**: Create quizzes for e-learning modules

## 🔧 Customization

The system can be adapted to support:

- Additional output formats
- Integration with Learning Management Systems
- Custom question templates
- Domain-specific knowledge bases

## 🐛 Troubleshooting

Common issues and solutions:

- **File Upload Issues**: Ensure the upload directory exists and has write permissions
- **PDF Generation Errors**: Verify wkhtmltopdf is properly installed
- **API Key Errors**: Check that your GOOGLE_API_KEY is correctly set as an environment variable
- **Empty Analysis Results**: Try with more comprehensive input content or adjust analysis parameters

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.

## 📬 Contact

Naman Singh - [@NamanSingh69](https://github.com/NamanSingh69)

Project Link: [https://github.com/NamanSingh69/exam-question-generator](https://github.com/NamanSingh69/exam-question-generator)

---

<div align="center">
Made with ❤️ for educators and students everywhere
</div>
