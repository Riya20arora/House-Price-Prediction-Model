House Price Prediction Web App
A simple Flask-based machine learning web application that predicts house prices based on user input. The model is trained using scikit-learn and integrated into a web interface built with Flask.

Features
Predict house prices using a trained ML model (model.pkl)

User-friendly input form (HTML + Flask)

Dynamic result rendering

Lightweight and easy to deploy

Project Structure
DMA FLASK/
│
├── templates/
│   ├── index.html          # Input form for prediction
│   └── result.html         # Result display page
│
├── App.py                  # Main Flask application
├── model.py                # Script to train and save the ML model
└── model.pkl               # Trained machine learning model
Model Info
Model: Logistic Regression (or any suitable regression model)

Input: Numeric value(s) representing house features (e.g., area, bedrooms, location index)

Output: Predicted house price

Libraries: scikit-learn, numpy, pickle, flask

⚙️ How to Run Locally
Install dependencies
pip install flask scikit-learn numpy

Train the model (optional, if model.pkl not present)
python model.py

Run the app
python App.py

Open in browser
eg [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

Sample Input & Output
Input Value (Area)	Predicted Price
1200	₹ 25,00,000
1800	₹ 35,00,000

Requirements
  Python 3.7+
  Flask
  scikit-learn
  numpy

Install using:
pip install -r requirements.txt
