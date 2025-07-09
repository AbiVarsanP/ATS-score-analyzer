# ATS Resume Score Analyzer

An AI-powered ATS (Applicant Tracking System) Resume Scoring Web App that evaluates your resume against job descriptions using semantic similarity. This model leverages Hugging Face's `sentence-transformers` for generating embeddings and computing cosine similarity scores.

> 🔗 Original model source: [Thirumurugan240/ATS-score-analyzer](https://github.com/Thirumurugan240)

---

## 🚀 Features

- Upload your resume and paste job description
- Uses Sentence Transformers to analyze textual relevance
- Calculates similarity score using cosine similarity
- Frontend built with HTML/CSS and Flask for backend

---

## 📁 Project Structure

```

ATS-score-analyzer/
│
├── app.py                # Main Flask backend
├── requirements.txt      # All dependencies
├── .env                  # Environment variables (create this)
├── static/
│   └── style.css         # Styling for the app
├── templates/
│   └── index.html        # Frontend template
└── README.md             # Project documentation

````

---

## ⚙️ Installation Steps

1. **Clone the Repository**

```bash
git clone https://github.com/AbiVarsanP/ATS-score-analyzer.git
cd ATS-score-analyzer
````

2. **Install Dependencies**

Ensure Python 3.8+ is installed.

```bash
pip install -r requirements.txt
```

3. **Create `.env` file**

Inside the root folder, create a `.env` file and add your Hugging Face API key:

```env
HUGGING_FACE_API=your_huggingface_api_key_here
```

4. **Run the Application**

```bash
python app.py
```

The app will run on `http://127.0.0.1:5000`

---
