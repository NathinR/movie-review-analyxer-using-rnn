# Movie Review Sentiment Analyzer 🎬 Using RNN

### 📌 Project Overview
This project uses a deep learning model built with TensorFlow to classify movie reviews as positive or negative. The model was trained on a dataset of IMDB reviews and can predict the sentiment of any new movie review entered by the user. The Streamlit app makes it easy to interact with the model through a user-friendly interface.

### 🚀 How to Run Locally (in Google Colab)
1. Install Streamlit:
```
!pip install streamlit -q
```
2. Check your public IP (optional):
```
!wget -q -O - ipv4.icanhazip.com
```
3. Run the Streamlit app and tunnel it using LocalTunnel:
```
!streamlit run app.py & npx localtunnel --port 8501
```

### 📁 Files in this Repository
* app.py – Streamlit application file
* sentiment_model.keras – Trained TensorFlow model in native format
* requirements.txt – All Python packages needed to run the app
* README.md – You’re reading it!

### ✅ Features
* Accepts user input movie reviews
* Predicts and displays sentiment: Positive 😊 or Negative 😞
* Runs seamlessly in Colab with live URL access via LocalTunnel

### 📌 Notes
* This app is optimized for quick testing and prototyping in Colab.
* To deploy publicly (like on Streamlit Cloud or HuggingFace Spaces), save all files and push this repo to GitHub first.

## The UI(Streamlit):
<img width="958" height="699" alt="Screenshot 2025-08-01 093508" src="https://github.com/user-attachments/assets/ad1e4dd8-8501-4dd4-8c02-39b47b272bab" />
