# email-spam-detection
# 📧 Email Spam Detection System

This project implements a **spam detection system** using **machine learning techniques** to classify email messages as either **spam** or **not spam**. It also demonstrates potential integration with **speech-to-text conversion** using OpenAI's Whisper for handling voice messages.

## 🚀 Project Overview

Spam emails are a persistent nuisance and can pose serious cybersecurity threats. This system was designed to:
- Preprocess and clean email text data
- Train a classification model (e.g., Naive Bayes, SVM)
- Evaluate the model's accuracy and performance
- Optionally integrate Whisper for converting audio to text for spam analysis

---

## 📁 Dataset

We use a cleaned dataset from Kaggle containing labeled spam and ham (non-spam) emails:

- ✅ Balanced classes
- ✅ Lightweight (<100MB)
- ✅ Ideal for fast training

[🔗 Kaggle Dataset](https://www.kaggle.com/datasets/purusinghvi/email-spam-classification-dataset)

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Scikit-learn | Machine learning models |
| Pandas & NumPy | Data manipulation |
| Matplotlib & Seaborn | Visualization |
| Jupyter Notebook | Development interface |
| OpenAI Whisper (optional) | Audio to text conversion |

---

## 🧠 Model Used

The notebook tests multiple classifiers:
- **Naive Bayes**
- **Logistic Regression**
- **Support Vector Machine (SVM)**

Performance is evaluated using:
- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix

---

## 🔮 Future Enhancements

- Integrate with Whisper to detect spam in voice messages
- Build a lightweight web app for user uploads
- Add adversarial training for robustness

---

## 📷 Project Screenshots

*(You can add images here)*  
`![](screenshots/pipeline.png)`  
`![](screenshots/results.png)`

---

## 🔗 Connect with Me

Built by [**Eman Ali**](https://www.linkedin.com/in/eman-ali/)  
View this project on LinkedIn via [Arch Technologies](https://www.linkedin.com/company/arch-technologies)

---

## 📌 License

This project is open-source and available under the [MIT License](LICENSE).
