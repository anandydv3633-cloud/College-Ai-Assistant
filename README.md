# 🎓 College AI Assistant

A Python-based College AI Assistant that helps students calculate attendance, analyze marks, manage timetable information, and get academic assistance using Google's Gemini AI.

## ✨ Features

- **Attendance Calculator:** Calculate attendance percentage and find how many consecutive classes you need to attend to reach your target.
- **Marks Calculator:** Calculate subject-wise marks, total marks, overall percentage, and target marks.
- **Timetable Analyzer:** Organize classes by day, identify free periods, and get AI-powered study-planning suggestions.
- **Gemini AI Chatbot:** Ask questions about engineering subjects, exam preparation, study plans, and college life.
- **Terminal Interface:** Simple command-line interface without Streamlit or a web framework.
- **Secure Configuration:** Store your Gemini API key in a `.env` file.

## 🛠️ Technologies Used

- Python
- Google Gemini API
- Google Gen AI Python SDK
- python-dotenv

## 📁 Project Structure

```text
college-ai-assistant/
│
├── app.py
├── llm_router.py
├── .env
├── .gitignore
├── requirements.txt
└── README.md
```

## ⚙️ Requirements

- Python 3.10 or newer
- Internet connection for Gemini AI features
- A valid Gemini API key

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/College-AI-Assistant.git
cd College-AI-Assistant
```

Replace `YOUR_USERNAME` with your GitHub username.

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Configure the
