# 🔥 Forest Fire Prediction Web App

This is a Flask-based web application that predicts the risk or impact of a forest fire based on environmental parameters like temperature, humidity, wind speed, and more. It uses a trained Ridge Regression model and Standard Scaler for preprocessing the data before making predictions.

---

## 🚀 Features

- Accepts input for key forest fire indicators.
- Scales input using pre-trained `StandardScaler`.
- Predicts fire intensity using a Ridge Regression model.
- User-friendly frontend built with HTML & Jinja2.
- Fully integrated with Flask for real-time predictions.

---

## 📁 Project Structure

FORESTFIRE_PREDICATION/
├── application.py                   # Main Flask application
├── models/                          # Serialized ML models
│   ├── ridge.pkl                    # Trained Ridge Regression model
│   └── scaler.pkl                   # StandardScaler for preprocessing
├── Notebooks/                       # Jupyter notebooks and dataset
│   ├── Algerian_forest_fires_dataset.csv  # Raw dataset used for training
│   └── FirstMl_Project.ipynb        # Exploratory data analysis and model training
├── templates/                       # HTML templates for frontend
│   ├── home.html                    # Form to input prediction data
│   └── index.html                   # Landing page
├── venv/                            # Python virtual environment (not included in version control)
├── requirements.txt                 # Python dependencies
└── README.md                        # Project documentation (this file)


## Author :- Professor Nitish Rao