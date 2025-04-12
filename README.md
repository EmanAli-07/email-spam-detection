# 📧 Email Spam Detection using Deep Learning (LSTM)

This project implements a **spam detection system** using a **Deep Learning model (LSTM)** built with **TensorFlow** and **Keras** to classify email messages as **spam** or **not spam**. It also demonstrates tokenization, sequence padding, and model saving for real-world deployment.

## 🚀 Project Overview

Spam detection is a critical task in communication systems. This project leverages deep learning to:
- Preprocess and tokenize email text data
- Build and train a Long Short-Term Memory (LSTM) model
- Save the trained model and tokenizer for future use
- Prepare for potential integration with OpenAI Whisper for audio message transcription


## 🧠 Deep Learning Model

The architecture includes:
- Embedding Layer (for word vectors)
- Bidirectional LSTM Layers
- Dropout Layers (to avoid overfitting)
- Dense Layer with Sigmoid Activation (for binary classification)

> 📁 Model is saved as `spam_detection_lstm.h5`  
> 📦 Tokenizer is saved as `tokenizer.pkl`

## 📁 Dataset

The model was trained on the combined dataset from Kaggle:

[🔗 Kaggle Email Spam Classification Dataset](https://www.kaggle.com/datasets/purusinghvi/email-spam-classification-dataset)

- Cleaned email messages labeled as spam or ham (not spam)
- Dataset used: `combined_data.csv`

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming |
| TensorFlow / Keras | Deep learning |
| Pandas / NumPy | Data manipulation |
| Scikit-learn | Preprocessing and splitting |
| Pickle | Model/tokenizer serialization |
| Jupyter Notebook | Development interface |

## 📊 Results

The model achieves:
- ✅ High accuracy on the validation set
- ✅ Fast convergence within 5 epochs
- ✅ Exportable and loadable for real-time use


## 🧪 Future Work

- Integrate Whisper (OpenAI) to convert voice to text for spam detection
- Deploy using Flask or Streamlit as a web app
- Add adversarial training for robustness

## 🙋‍♀️ Author

Made by **Eman Ali**  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/eman-ali/)

## 📄 License

This project is licensed under the [MIT License](LICENSE).
