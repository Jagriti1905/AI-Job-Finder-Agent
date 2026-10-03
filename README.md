# AI-Job-Finder-Agent
AI-powered job recommendation agent using Python, Gradio and OpenAI.
# 🤖 AI Job Finder Agent

An AI-powered job recommendation agent that helps users find relevant internship and entry-level job opportunities based on their skills, preferred role, location, experience, and resume.

## 🚀 Features

- 🔍 Search jobs based on user skills
- 💼 Filter jobs by preferred role
- 📍 Filter jobs by location
- 🎓 Filter jobs by experience level
- 📄 Upload a resume (PDF, DOCX, or TXT)
- 🤖 Automatically extract technical skills from the resume
- ⭐ Calculate job match score
- 🛠️ Show matched skills
- ⚠️ Identify missing skills
- 💡 Explain why a job matches the user
- 🔗 Provide an Apply Now link
- 🖥️ Simple interactive Gradio interface

## 🛠️ Technologies Used

- Python
- Pandas
- OpenAI API
- Gradio
- PyPDF
- python-docx

## 🧠 How It Works

1. User enters their desired job role.
2. User provides their skills or uploads a resume.
3. The system extracts skills from the resume using AI.
4. Jobs are filtered according to role, location, and experience.
5. The system compares the user's skills with job requirements.
6. A match score is calculated.
7. The agent displays recommended jobs along with matched and missing skills.

## 📊 Match Score

The match score is calculated based on the percentage of required job skills that match the user's skills.

For example:

- Required skills: Python, SQL, Pandas, Excel
- User skills: Python, SQL, Pandas
- Match Score: 75%

## 📄 Resume Analysis

The agent supports:

- PDF resumes
- DOCX resumes
- TXT resumes

The uploaded resume is processed to identify relevant technical skills.

## 🖥️ Demo

The project includes a Gradio-based web interface where users can enter their preferences and receive job recommendations.

## 📁 Project Structure

```text
AI-Job-Finder-Agent/
│
├── AI_Job_Finder_Agent.ipynb
├── README.md
└── requirements.txt
