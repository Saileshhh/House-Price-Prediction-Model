🏡 House Price Prediction App

An interactive Machine Learning web application built with Streamlit that predicts house prices based on multiple property features using a trained XGBoost model.

🔗 Live App:
👉 https://housing-price-forecast.streamlit.app/

📘 Overview

This project leverages an XGBoost Regressor trained on housing data to estimate house prices.
The app provides a clean and user-friendly interface where users can input property details and instantly view a predicted price.

✨ Features

🧠 Machine Learning Powered — uses a trained XGBoost model

⚡ Real-time Predictions

🖥 Responsive Streamlit Web UI

🔧 Handles categorical encoding (CentralAir)

☁️ Hosted live on Streamlit Cloud

🧠 Model Details

Algorithm: XGBRegressor

Framework: XGBoost

Model File: xgb_model.jb (loaded via joblib)

Input Fields: 15 numerical + 1 categorical

📥 Features Used in Prediction
Feature	Description
OverallQual	Overall material and finish quality
GrLivArea	Above grade (ground) living area
GarageArea	Garage size in square feet
1stFlrSF	First floor square feet
FullBath	Full bathrooms above grade
YearBuilt	Original construction date
YearRemodAdd	Remodel year
MasVnrArea	Masonry veneer area
Fireplaces	Number of fireplaces
BsmtFinSF1	Finished basement area
LotFrontage	Linear feet of street connected to property
WoodDeckSF	Wood deck area
OpenPorchSF	Open porch area
LotArea	Lot size in square feet
CentralAir	Air conditioning: Yes/No

📁 Project Structure
📦 House Price Prediction App
├── app.py               # Streamlit main application
├── xgb_model.jb         # Trained XGBoost model
├── README.md            # Documentation
└── requirements.txt     # Dependencies

🚀 Deployment

This app is deployed using Streamlit Community Cloud.

🤝 Contributing

Contributions, feature requests, and suggestions are welcome.

📜 License

This project is open-source and free to use.

