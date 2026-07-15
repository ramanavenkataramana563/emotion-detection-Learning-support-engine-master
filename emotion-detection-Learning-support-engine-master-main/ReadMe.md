 🎓 Emotion Detection & Learning Support Engine

An AI-powered learning support platform that detects learner emotions from free-text input using **BiLSTM** and **BERT** models and generates personalized learning guidance using **Google Gemini AI**.

---

## 📌 Features

- 😊 Emotion Detection using BiLSTM
- 🧠 Context-Aware Emotion Classification using BERT
- 🔀 Mixed Emotion Detection
- 💡 AI-Powered Learning Guidance using Google Gemini AI
- 📊 Emotion Analytics Dashboard
- 📈 Study Field-wise Emotion Analysis
- 📝 Session History & CSV Logging
- ⚖️ BiLSTM vs BERT Model Comparison
- 🎨 Interactive Streamlit Interface

---

## 🏗️ Project Architecture

```text
User
  │
  ▼
Streamlit Application
  │
  ▼
Text Preprocessing
  │
 ├── BiLSTM Model
 ├── BERT Model
  │
  ▼
Mixed Emotion Detection
  │
  ▼
Google Gemini AI
  │
  ▼
Analytics & Session History

---

## 📂 Project Structure

```text
emotion-detection-learning-support-engine/
│
├── data/
├── docs/
├── models/
│   ├── bert/
│   └── bltsm/
├── notebooks/
├── src/
├── app.py
├── requirements.txt
├── README.md
└── .env

---

## ⚙️ Technologies Used

| Technology         | Purpose                    |
| ------------------ | -------------------------- |
| Streamlit          | Web Application            |
| TensorFlow & Keras | BiLSTM Model               |
| PyTorch            | BERT Backend               |
| Transformers       | BERT Emotion Detection     |
| Google Gemini AI   | Personalized Guidance      |
| Pandas             | Data Processing            |
| NumPy              | Numerical Computing        |
| NLTK               | Text Preprocessing         |
| Scikit-learn       | Preprocessing & Evaluation |
| Plotly             | Analytics Dashboard        |
| Matplotlib         | Visualization              |
| Joblib             | Model Serialization        |


---

## 🚀 Installation

### 1. Clone Repository

```bash
git clone hhttps://github.com/ramanavenkataramana563/emotion-detection-Learning-support-engine-master

cd emotion-detection-learning-support-engine

python -m venv .venv

### 2. Create Virtual Environment

```bash
python -m venv .venv
```

Activate environment:

**Windows**

```bash
.venv\Scripts\activate
```

**Linux / macOS**

```bash
source .venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Create .env

GEMINI_API_KEY=YOUR_GEMINI_API_KEY

```

---

## ▶️ Run Frontend

```bash
streamlit run app.py
```

Frontend runs at:

```text
http://localhost:8501
```

---

## 🧪 Running Tests

Run all test cases:

```bash
pytest -v
```

Example output:

```text
================ 5 passed =================
```

---


## 🌟 Future Enhancements

User Authentication
Cloud Deployment
Database Integration
Mobile Application
Multilingual Support
Teacher Dashboard

---

## 👨‍💻 Author

**Course : Google Cloud Generative AI**

**AITS Kadapa**

**B.Tech CSE (AI & DS)**


**pavan p**
Email : ramanavenkataramana563@gmail.com
Roll No. : 23HM1A3018
GitHub: https://github.com/ramanavenkataramana563/emotion-detection-Learning-support-engine-master



---

## 📜 License

This project was developed as part of an internship project for educational purposes.
# emotion-detection-Learning-support-engine-master
