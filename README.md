# Job Finder Master

A Flask-based web application that helps users upload their resume and get the **best matching jobs** based on their skills.

## 🚀 Features
- Upload resumes in **PDF, DOCX, DOC, or TXT** format.
- Extracts **skills, education, experience, and contact info** from resumes.
- Analyzes skills and provides a skill breakdown.
- Suggests **matching job roles** from multiple categories.
- Simple web interface with results page.
- REST API endpoints for skills and job categories.

## 🛠️ Tech Stack
- **Backend:** Flask (Python)
- **Libraries:** pdfminer, PyPDF2, python-docx
- **Frontend:** HTML (Jinja2 templates)
- **Others:** Session management, file upload handling

## 📂 Project Structure
# Job-Finder-Master
Job-finder-master/
│── app.py # Main Flask app
│── resume_parser.py # Extracts info from resumes
│── requirements.txt # Dependencies
│── templates/ # HTML templates (index.html, results.html, etc.)
│── static/ # CSS, JS, images
│── uploads/ # Uploaded resumes
