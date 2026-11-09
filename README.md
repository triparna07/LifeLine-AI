# LifeLine AI 🛡️

### AI-Powered Digital Safety and Emergency Awareness Platform

LifeLine AI is an AI-powered web application designed to help people identify potential online scams, suspicious messages, cyber threats, and emergency situations.

It uses Google's Gemini AI to analyze text and uploaded screenshots, identify warning signs, assess potential risks, and provide simple, practical safety recommendations.

## ✨ Features

- **AI-Powered Text Analysis:** Analyze suspicious messages and situations using Gemini AI.
- **Screenshot Analysis:** Upload screenshots to identify suspicious text, links, payment requests, and other warning signs.
- **Risk Assessment:** Classifies situations into Low, Medium, High, Critical, or Uncertain risk levels.
- **Safety Recommendations:** Provides easy-to-understand explanations and practical safety steps.
- **Emergency Awareness:** Identifies situations that may require urgent assistance.
- **Analysis History:** Stores previous analysis results using SQLite.
- **Responsive Interface:** Designed to work on desktop and mobile devices.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Flask | Web application framework |
| Google Gemini API | AI-powered analysis |
| HTML | Web page structure |
| CSS | User interface and styling |
| JavaScript | Frontend interactions |
| SQLite | Analysis history database |
| Pillow | Image processing |
| Gunicorn | Production WSGI server |
| Render | Cloud deployment |
| GitHub | Source code management |

## ⚙️ How It Works

1. The user enters a suspicious message or uploads a screenshot.
2. The application sends the provided content to the Flask backend.
3. Gemini AI analyzes the content and identifies possible warning signs.
4. The application generates a risk classification and safety recommendations.
5. The result is displayed to the user.
6. The analysis result is stored in the SQLite database.

## 🚀 Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/triparna07/LifeLine-AI.git
```

### 2. Open the project folder

```bash
cd LifeLine-AI
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows PowerShell:**

```powershell
.\venv\Scripts\Activate.ps1
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Configure your Gemini API key

Create a file named `.env` in the project folder.

Add:

```env
GEMINI_API_KEY=your_gemini_api_key
```

Replace the placeholder with your own Gemini API key.

### 7. Run the application

```bash
python app.py
```

Open your browser and visit:

```text
https://lifeline-ai-cfu4.onrender.com

```
## 🌐 Live Demo

Try LifeLine AI here:
https://lifeline-ai-cfu4.onrender.com


## ☁️ Deployment

LifeLine AI is deployed using **Render**.

The application is connected to its GitHub repository and runs as a Python Flask web service using Gunicorn.

The Gemini API key is configured through Render environment variables rather than being stored in the source code.

## 🔐 Privacy and Safety

- API keys should never be committed to GitHub.
- User-provided messages and screenshots should be treated as untrusted content.
- The application stores analysis results in its SQLite history database.
- Users should never share passwords, OTPs, PINs, or confidential banking information.
- AI-generated results are informational and should not replace professional assistance or emergency services.

## ⚠️ Disclaimer

LifeLine AI is an AI-assisted safety awareness tool. Its analysis may not always be accurate and should not be treated as a guarantee that a message or situation is safe.

In India:
- Emergency assistance: **112**
- Financial cyber fraud helpline: **1930**
- Official cybercrime portal: https://cybercrime.gov.in/

## 👩‍💻 Developer

**Triparna Nag**

Computer Science and Engineering Student

IEM Kolkata

---

*LifeLine AI — Stay Aware. Stay Safe.*
