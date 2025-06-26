🏡 Bangalore House Price Prediction (ML Web App)
This is my Machine Learning and Flask web application project that predicts house prices in Bangalore. I trained different models on real housing data and created a website where users can input house details and get the predicted price instantly.

🔍 Project Highlights
🔢 Inputs: Location, Square Feet, BHK, Bathrooms

📈 Models: Linear Regression, Random Forest, XGBoost

🧠 Best model: XGBoost (R² ≈ 0.69)

🖥️ Built with: Python, Pandas, Scikit-learn, Flask, HTML, CSS, Bootstrap

🌐 Features:

House price prediction

Compare two locations by average price

Trend analysis with graphs

🗂️ Files & Folders
php
Copy
Edit
.
├── app.py                # Main Flask backend
├── model.pkl             # Trained ML model
├── scaler.pkl            # StandardScaler for preprocessing
├── predictions.csv       # Cleaned data for comparison
├── templates/            # HTML files (index, predict, compare, about)
├── static/               # CSS/JS and images
├── model3.ipynb          # Jupyter notebook with EDA + training
├── realtor-data.zip.csv  # Raw housing dataset




Models Performance
Model	R² Score
Linear Regression	0.30
Random Forest	0.67
XGBoost ✅	0.69

I selected XGBoost for best results and saved it as model.pkl.

✨ Project Features in Web Interface
✅ User input prediction
✅ Compare average price between two locations
✅ Price trend analysis chart
✅ Responsive design with Bootstrap

📌 What I Learned
Data cleaning and feature engineering

Handling categorical and numerical features

Building regression models

Saving models with pickle

Creating a Flask app with HTML/CSS templates

Deploying model into a real interface

🙋‍♂️ About Me
👋 I'm Mohammed Ziyad — beginner in ML and Web Development.
