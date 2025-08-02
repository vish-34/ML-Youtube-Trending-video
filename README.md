# 🔥 YouTube Virality Prediction Model

A simple machine learning model that predicts whether a YouTube video will go **viral** based only on its **title** — for now.  
In the future, the model will expand to include more features like tags, views, likes, thumbnails, and more.

---

## 📊 Dataset

- Source:(https://amanxai.com/2020/11/28/youtube-trending-videos-analysis-with-python/)
- Current Feature: `title`
- Target: Viral (based on a views threshold)

---

## 🧠 What It Does (Current Scope)

- Cleans and processes video titles  
- Converts titles into TF-IDF vectors  
- Trains a binary classifier to predict virality (Logistic Regression)  
- Returns predictions with confidence scores  

---

## 🚧 Future Scope

In the next version, the model will:
- Include features like tags, likes, publish time, and description  
- Use advanced classifiers (XGBoost, Random Forests, etc.)  
- Possibly deploy via a simple UI/web app  

---

## 💡 Example Output

```python
Title: "You Won't Believe This AI Trick!"
Prediction: Viral ✅  
Confidence: 81%
