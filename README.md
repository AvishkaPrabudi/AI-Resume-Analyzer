 AI Resume Analyzer (Python + Flask + Gemini)

This project is a web-based AI tool that analyzes a resume against a job description using Google Gemini AI. It extracts resume content from a PDF, sends it to the AI model, and generates:

✅ Match Score
✅ Missing Skills
✅ Suggestions for Improvement
✅ Summary

Built using Python, Flask, PyMuPDF, and Gemini AI.

 Features

✅ Upload PDF Resume
✅ Extract text automatically
✅ AI-powered resume analysis
✅ Score out of 100
✅ Highlights missing skills
✅ Suggestions for improvement
✅ Simple Flask web interface

🛠️ Tech Stack
Component	Technology
Backend	Python + Flask
AI Model	Gemini 1.5 Flash
PDF Reader	PyMuPDF (fitz)
Frontend	HTML (Jinja Template)
📂 Project Structure
Resume_Analyser_Using_Python/
│
├── analyse_pdf.py          # AI logic using Gemini
├── main.py                 # Flask web server
├── uploads/                # Uploaded resumes
├── templates/
│   └── index.html          # Web UI
├── .env                    # API key (not pushed to GitHub)
└── README.md

✅ Requirements

Install Python dependencies:

pip install flask pymupdf python-dotenv google-generativeai

🔑 Environment Setup

Create a .env file in the project root:

GEMINI_API_KEY=YOUR_API_KEY_HERE



▶️ How to Run the Project

1️⃣ Open terminal inside the project folder
2️⃣ Run the Flask app:

python main.py




4️⃣ Upload a PDF + enter job description
5️⃣ View AI analysis result ✅

🧩 How It Works

1️⃣ User uploads a PDF
2️⃣ PyMuPDF extracts text
3️⃣ Text + Job Description are sent to Gemini AI
4️⃣ AI analyzes and returns:

Match score

Missing skills

Suggestions

Summary

5️⃣ Results are displayed on the webpage
