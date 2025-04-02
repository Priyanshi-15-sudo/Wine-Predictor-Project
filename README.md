🍷 Wine Quality Predictor
📌 Overview
The Wine Quality Predictor is a Flask-based web application that predicts the quality of wine based on its chemical properties. Users input various wine characteristics, and the model classifies the wine as "Good Quality" or "Bad Quality" using a trained machine learning model.

📂 Project Structure
app.py – The Flask backend that loads the trained model and handles predictions.

wine_quality_model.pkl – Pre-trained machine learning model used for wine quality classification.

index.html – A simple and interactive front-end for users to input wine features and get predictions.

🚀 How It Works
Users enter wine-related chemical parameters like acidity, pH, alcohol content, etc.

The Flask API processes the input and sends it to the trained machine learning model.

The model predicts whether the wine is of good or bad quality and displays the result on the webpage.

🛠 Technologies Used
Python (Flask, NumPy, Joblib)

Machine Learning (Pre-trained model for classification)

HTML, CSS & JavaScript (Frontend for user interaction)
