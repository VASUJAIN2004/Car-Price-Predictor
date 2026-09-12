Machine learning model and web application to predict used car prices using regression algorithms and vehicle dataset features.
# 🚗 Car Price Predictor (Flask App)

A machine learning-powered web application built with **Flask** that estimates the resale price of a used car based on features such as brand, year, kilometers driven, fuel type, and transmission.

👉 **Live Demo:** [https://car-price-predictor-4-5h4q.onrender.com](https://car-price-predictor-4-5h4q.onrender.com)

---

## 🌟 Features
- **Accurate Predictions:** Uses a trained machine learning regression model saved via Pickle/Joblib.
- **Interactive Web Interface:** Built using HTML/CSS templates rendered dynamically via Flask.
- **Real-Time Estimation:** Instant price computation right on the web browser.
- **Cloud Deployment:** Seamlessly hosted on Render.

---

## 🛠️ Tech Stack
- **Backend Framework:** Python, Flask
- **Machine Learning:** Scikit-Learn, Pandas, NumPy
- **Frontend:** HTML5, CSS3, Bootstrap (or custom CSS)
- **Deployment:** Render (`Gunicorn` / `Procfile`)

---

## 📂 Project Structure
```text
car-price-predictor/
│
├── static/              # CSS files, images, and styling assets
├── templates/           # HTML templates (index.html, result.html)
├── model/               # Trained machine learning model (.pkl file)
├── app.py               # Main Flask application logic
├── requirements.txt     # Python dependencies
├── Procfile             # Render deployment configuration
└── README.md            # Project documentation
