# 📧 Email/SMS Spam Classifier

A Machine Learning web application that detects whether a given Email or SMS message is **Spam** or **Not Spam** — built with Python, NLP, and Streamlit.

---

## 🧠 How It Works

1. User enters an Email or SMS message
2. Text is preprocessed using NLP techniques (lowercasing, tokenization, stopword removal, stemming)
3. The cleaned text is vectorized using a **TF-IDF Vectorizer**
4. A pre-trained **ML model** predicts: 🚨 Spam or ✅ Not Spam

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | Python |
| Web Framework | Streamlit |
| NLP Library | NLTK |
| ML Model | Scikit-learn |
| Vectorizer | TF-IDF |
| Deployment | Heroku |

---

## 📁 Project Structure
ml-project/
│
├── app.py              # Main Streamlit application
├── model.pkl           # Pre-trained ML classification model
├── vectorizer.pkl      # TF-IDF vectorizer
├── requirements.txt    # Python dependencies
├── Procfile            # Heroku deployment config
└── setup.sh            # Streamlit server setup script

---

## ⚙️ Installation & Setup

### 1. Clone the repository
git clone https://github.com/v-singh145/ml-project.git
cd ml-project

### 2. Install dependencies
pip install -r requirements.txt

### 3. Run the app
streamlit run app.py

---

## 📊 Features

- Clean and minimal UI built with Streamlit
- Real-time spam detection on any text input
- NLP pipeline: tokenization → stopword removal → stemming → TF-IDF
- Pre-trained model loaded via pickle for fast inference

---

## 👤 Author

**v-singh145**
https://github.com/v-singh145
