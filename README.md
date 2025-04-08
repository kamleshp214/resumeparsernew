# 🧠 Resume Parser ATS (AI-Powered)

An AI-powered Resume Parser and Applicant Tracking System (ATS) that extracts structured information from resumes (PDF/DOCX), calculates ATS scores, and allows filtering/searching by skills and experience.

> ⚙️ Powered by **Python Flask** backend, **JavaScript/Bootstrap** frontend, and **spaCy NLP** for AI-based information extraction.

GitHub Repo: [https://github.com/kamleshp214/resumeparsernew](https://github.com/kamleshp214/resumeparsernew)

---

## ✨ Features

- Upload multiple resumes in PDF or DOCX format
- Extract key fields: Name, Email, Phone, Skills, Education, Experience
- **AI-enhanced skill extraction** using spaCy NLP
- Search resumes by specific skills
- Sort candidates based on ATS score
- Responsive UI with modern glassmorphism styling
- ATS Score visual comparison between candidates
- Clean JSON-based data structure and modular code

---

## 🧠 AI Integration

This project initially attempted integration with cloud-based AI APIs (e.g., OpenAI, Cohere) for parsing resumes using advanced language models.  
However, due to **API limitations and cost constraints**, a robust and offline-friendly solution was implemented using:

> 🔍 **[spaCy](https://spacy.io/)** – A local machine learning NLP library for fast and accurate resume parsing.

spaCy ensures full control, speed, and accuracy without relying on external paid services.

---

## ⚙️ Setup & Installation

### 1. Clone the Repository
git clone https://github.com/kamleshp214/resumeparsernew.git
cd resumeparsernew
2. Install Dependencies
pip install -r requirements.txt
✅ Python 3.8+ recommended
3. Download spaCy NLP Model
python -m spacy download en_core_web_sm
4. Run the Flask App
python app.py
5. Open in Your Browser
http://localhost:5000
🖥️ Frontend Features
Built with HTML, CSS, JavaScript, and Bootstrap

Clean, gradient-based UI with glassmorphism elements

Toast notifications for upload and parsing

Search bar to filter candidates by skills

Responsive layout for desktop and mobile

Side-by-side resume view with ATS score bars

📁 Project Structure
resumeparsernew/
│
├── static/                # Frontend assets (CSS/JS)
├── templates/             # HTML Templates
├── uploads/               # Uploaded resume files
├── parser/                # spaCy NLP logic
├── app.py                 # Flask backend
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
💡 Future Enhancements
Job description upload for more accurate ATS scoring

AI vs. keyword toggle option

CSV/JSON export of parsed data

Cloud deployment version (Render, Vercel, etc.)

Admin dashboard and resume analytics

🤝 Contributing
Pull requests and suggestions are welcome. Let’s build something awesome together!

📜 License
This project is licensed under the MIT License.
