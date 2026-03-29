# Krrish-kumar_25SCS1003001521_IILMGN
Machine Learning based spam email classifier with Gmail automation using Python and Naive Bayes.
# 📧 Spam Email Classifier (Python + ML)

This project is a **Spam Email Classifier** built using Machine Learning.  
It can classify emails as **Spam 🚨 or Ham ✅ (Not Spam)** and even connect to your Gmail inbox to automatically filter unread emails.

---

## 🚀 Features

- Train a spam detection model using email dataset
- Classify custom messages
- Connect to Gmail using IMAP
- Automatically detect spam emails
- Move spam emails to Gmail Spam folder

---

## 🧠 Tech Stack

- Python
- Pandas
- Scikit-learn
- IMAP (Gmail integration)

---

## 📂 Project Structure

```
spam-email-classifier/
│── spam_email_classifier.py
│── emails.csv
│── README.md
│── requirements.txt
```

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/spam-email-classifier.git
cd spam-email-classifier
pip install -r requirements.txt
```

---

## ▶️ Usage

```bash
python spam_email_classifier.py
```

---

## 🔐 Important (Security Notice)

⚠️ **DO NOT upload your real email credentials to GitHub**

Instead of hardcoding:
```python
EMAIL_USER = "your_email@gmail.com"
EMAIL_PASS = "your_app_password"
```

Use environment variables:
```bash
export EMAIL_USER="your_email@gmail.com"
export EMAIL_PASS="your_app_password"
```

---

## 🧪 Example Output

```
Subject: Win a free iPhone now!!!
Prediction: Spam 🚨
```

---

## 📊 Machine Learning Model

- Vectorization: CountVectorizer
- Algorithm: Multinomial Naive Bayes
- Train/Test Split: 80/20

---

## 💡 Future Improvements

- Add GUI (Tkinter or Web App)
- Use NLP models (TF-IDF, BERT)
- Real-time email notifications
- Deploy as a web service

---

## 🤝 Contributing

Pull requests are welcome!

---

## ⭐ Don't forget to star this repo!
