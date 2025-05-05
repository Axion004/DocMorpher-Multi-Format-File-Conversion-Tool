DocMorpher: Multi-Format File Conversion Tool

**DocMorpher** is a simple Flask-based web application that converts uploaded `.txt` or `.doc/.docx` documents into three different formats: PDF, PMD (custom), and CDR (custom). It's designed to provide a user-friendly interface for document transformation using Python libraries.

## 🚀 Features

- Upload `.txt`, `.doc`, or `.docx` files
- Convert to:
  - 📄 PDF using ReportLab
  - 📘 PMD format (custom text serialization)
  - 📕 CDR format (custom text serialization)
- Web interface with upload and results view

## 🧰 Technologies Used

- Flask
- python-docx
- ReportLab
- HTML/CSS (via Jinja2 templates)

## 🛠️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/docmorpher.git
   cd docmorpher
Create a virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies

pip install -r requirements.txt
Prepare folder structure
Ensure an uploads/ directory exists in the root folder:

mkdir uploads
Run the application

python app.py
Access the app in your browser
Visit http://127.0.0.1:5000 to upload and convert files.

📁 Project Structure

├── app.py                # Main Flask app
├── templates/
│   ├── index.html        # Upload form
│   └── result.html       # Display output links
├── uploads/              # Stores uploaded & converted files
├── requirements.txt
└── README.md
