
# AI-Powered Resume Analyzer
A Python web application that uses machine learning to analyze and score resumes based on job descriptions.

## 🌟 Features
- Analyze and score resumes based on job descriptions.
- Provide detailed feedback on skills, experience, education, and resume structure.
- User-friendly interface with a modern look.
- Responsive design for various devices.
- Developed using Flask, HTML, CSS, and JavaScript.
- Machine learning model to provide smart analysis and recommendations.

### Analysis Screen
- Displays the overall resume score and detailed feedback on different aspects such as skills match, experience match, education match, and resume structure.

## 🛠️ Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python, Flask
- **Machine Learning**: spaCy, transformers, scikit-learn
- **Other Libraries**: Flask-WTF for form handling, docx for resume parsing

## 📝 Setup Instructions
Follow these steps to set up the project locally:

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/AI_Resume_Analyzer.git
cd AI_Resume_Analyzer
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Download and Install SpaCy Model
```bash
python -m spacy download en_core_web_sm
```

### 5. Run the Application
```bash
python run.py
```

## 📄 Project Structure
```plaintext
resume_analyzer/
├── app/
│   ├── main/
│   │   ├── static/
│   │   │   ├── css/
│   │   │   │   └── styles.css
│   │   │   ├── js/
│   │   │   │   └── scripts.js
│   │   ├── templates/
│   │   │   ├── base.html
│   │   │   └── index.html
│   │   ├── __init__.py
│   │   ├── routes.py
│   │   ├── forms.py
│   ├── __init__.py
├── models/
│   ├── __init__.py
│   ├── resume_parser.py
│   ├── job_description_parser.py
│   ├── resume_scorer.py
├── tests/
│   ├── test_routes.py
│   └── test_models.py
├── .gitignore
├── README.md
├── requirements.txt
└── run.py
```
