# AI-Resume-Ranker
# Resume Ranker Web App :

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)


## Features

- Upload job descriptions and resumes in PDF format.
- Process resumes to extract names, emails, and text content.
- Calculate the similarity between the job description and each resume.
- Rank resumes based on similarity percentage.
- Download the ranked resumes in a CSV file.
- Dark Mode Contributed by @hbalickgoodman 

## Setup and Usage

1. Clone the repository: https://github.com/Aryanjali-25/AI-Resume-Ranker.git

2. Navigate to the project directory: cd resume-analyzer


3. Install dependencies (Install the latest libraries instead of the specific ones mentioned in the txt file):
   pip install -r requirements.txt

4. Run the Flask app: python app.py

5. Access the app in your web browser at `http://localhost:5000`.

## :file_folder: Directory Structure
----------
├── app.py
├── static/
│   └── styles.css
├── templates/
│   └── index.html
├── uploads/             # Uploaded resumes will be saved here
├── requirements.txt
├── README.md
└── .gitignore

----------

## Inspiration

This project was inspired by the desire to create an interactive tool for HR professionals to easily analyze job applicants' resumes.


