# 📧 Email Engagement Prediction 

This project is a Streamlit-based web application that predicts email engagement (Opened, Clicked, or both) based on metadata such as hour, day, country, and email content. It also provides optimization insights such as best time, day, and region to send campaigns for maximum engagement.

---

## 🚀 Features

- 🔍 Predicts email engagement category (Opened, Clicked, Opened+Clicked)
- 📈 Shows key engagement metrics (Open Rate, Click Rate, Engagement Score)
- 🧠 Offers data-driven optimization tips
- 🌍 Identifies best-performing hours, days, and regions
- 🖥️ Built with Streamlit for an interactive UI
- ✅ Trained with a pipeline model and saved using `joblib`

---

## 🧠 Model Details

- Uses XGBoost
- Uses a machine learning pipeline trained on features:
  - `hour`, `weekday`, `user_country`, `email_text`, `email_version`
- Predicts 3 engagement classes using `predict_proba`
- Optimized metrics include:
  - Top 3 hours, days, and regions for better engagement
- Model and metrics are saved as:
  - `email_engagement_model.joblib`
  - `email_engagement_metrics.joblib`

---

## 📁 Project Structure

📦 email-engagement-predictor
|-- app.py                        # Streamlit app UI
|-- email_engagement_model.joblib    # Trained ML model
|-- email_engagement_metrics.joblib  # Pre-calculated insights
|-- requirements.txt             # Python dependencies
|-- code.ipynb 
|-- dataset
|-- Deployment Screenshots
└-- README.md

![Screenshot 2025-06-29 120601](https://github.com/user-attachments/assets/b8418fe6-f509-443c-9601-60a254e3bf2b)

## - Ritesh Raj


