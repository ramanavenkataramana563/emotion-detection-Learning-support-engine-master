# 🎓 Emotion Detection & Learning Support Engine

An AI-powered learning support platform that detects students' emotions from text using **BiLSTM** and **BERT** deep learning models and generates personalized learning guidance using **Google Gemini AI**.

The application helps students overcome learning difficulties by providing emotion-aware recommendations, interactive analytics, and personalized academic support.

---

# 📌 Features

- 😊 Emotion Detection using BiLSTM
- 🤖 Context-Aware Emotion Classification using BERT
- 🔀 Mixed Emotion Detection
- 💡 AI-Powered Learning Guidance using Google Gemini AI
- 📊 Emotion Analytics Dashboard
- 📈 Emotion Distribution & Study Field Analysis
- 📝 Session History & CSV Logging
- ⚖️ BiLSTM vs BERT Model Comparison
- 🎨 Interactive Streamlit Dashboard

---

# 🏗️ Project Architecture

```text
                    User
                      │
                      ▼
          Streamlit Web Application
                      │
                      ▼
             Text Preprocessing
                      │
          ┌───────────┴───────────┐
          ▼                       ▼
    BiLSTM Model            BERT Model
          │                       │
          └───────────┬───────────┘
                      ▼
          Mixed Emotion Detection
                      │
                      ▼
         Google Gemini AI Guidance
                      │
                      ▼
       Analytics & Session History
                      │
                      ▼
                CSV Data Storage
```

---

# 📂 Project Structure

```text
emotion-detection-learning-support-engine/
│
├── data/
│   ├── emotion_response_examples.csv
│   ├── emotion_response_mapping.csv
│   └── emotion_text_dataset.csv
│
├── docs/
│
├── models/
│   ├── bert/
│   └── bltsm/
│
├── notebooks/
│   ├── bert_train.py
│   └── train_bilstm.py
│
├── src/
│   ├── bert_model.py
│   ├── bilstm_predictor.py
│   ├── preprocessing.py
│   ├── mixed_emotion.py
│   ├── emotion_responses.py
│   ├── gemini_helper.py
│   └── check_models.py
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

# ⚙️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Core Programming Language |
| Streamlit | Interactive Web Interface |
| TensorFlow & Keras | BiLSTM Model |
| PyTorch | BERT Backend |
| Hugging Face Transformers | BERT Emotion Classification |
| Google Gemini AI | Personalized Learning Guidance |
| Pandas | Data Processing |
| NumPy | Numerical Computing |
| Scikit-learn | Preprocessing & Evaluation |
| NLTK | Text Preprocessing |
| Plotly | Analytics Dashboard |
| Matplotlib | Model Evaluation Graphs |
| Joblib | Save/Load Tokenizers & Encoders |

---

# 🚀 Installation

## 1. Clone Repository

```bash
git clone https://github.com/lokeshluckey2009-sys/emotion-detection-learning-support-engine.git
```

```bash
cd emotion-detection-learning-support-engine
```

---

## 2. Create Virtual Environment

```bash
python -m venv .venv
```

Activate the environment

### Windows

```bash
.venv\Scripts\activate
```

### Linux / macOS

```bash
source .venv/bin/activate
```

---

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4. Configure Environment Variables

Create a `.env` file and add:

```env
GEMINI_API_KEY=YOUR_GEMINI_API_KEY
```

---

## 5. Verify Models

Ensure the following folders exist:

```text
models/
├── bert/
└── bltsm/
```

---

# ▶️ Run the Application

```bash
streamlit run app.py
```

The application runs at:

```text
http://localhost:8501
```

---

# 📷 Application Screenshots

- Home Page
- Emotion Prediction Dashboard
- BiLSTM vs BERT Comparison
- AI Learning Guidance
- Emotion Analytics Dashboard
- Study Field Analysis

---

# 🌟 Future Enhancements

- User Authentication
- Cloud Deployment (AWS / Google Cloud / Azure)
- MongoDB / PostgreSQL Integration
- Mobile Application
- Multilingual Emotion Detection
- Teacher Dashboard
- Real-Time Learning Analytics
- Advanced Personalized Learning Recommendations

---

# 👨‍💻 Team Members

**Project:** Emotion Detection & Learning Support Engine

**Team Size:** 5 Members

- Member 1 – Team Leader
- Member 2 – AI/ML Developer
- Member 3 – Backend Developer
- Member 4 – Frontend Developer
- Member 5 – Documentation & Deployment

---

# 📜 License

This project was developed as part of the **SmartBridge / SkillWallet Generative AI Internship** for educational purposes.