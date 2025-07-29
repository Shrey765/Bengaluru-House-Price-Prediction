![Python](https://img.shields.io/badge/Python-3.8-blue)
![Flask](https://img.shields.io/badge/Flask-WebFramework-lightgreen)
![ML](https://img.shields.io/badge/Model-RidgeRegression-orange)
![Status](https://img.shields.io/badge/Status-Working-brightgreen)


<p align="center">
  <img src="images/Screenshot 2025-07-29 at 11.48.33 PM.png" alt="App Preview" width="800"/>
</p>



# 🏠 House Price Prediction Web App

A web-based application built with **Flask**, **scikit-learn**, and **Bootstrap** that predicts house prices based on location, number of bedrooms (BHK), bathrooms, and total square feet.

---

## 🚀 Features

- Predict house prices using a trained **Ridge Regression** model.
- Dynamic form populated with only valid input values:
  - Locations from the dataset.
  - Valid BHK and bathroom counts.
  - Square footage restricted between dataset min and max.
- Smooth user experience using **AJAX** (no page reloads).
- Clean, responsive **Bootstrap** interface.

---

## 🧠 Model Details

- **Model Used**: Ridge Regression (sklearn)
- **Trained On**: Cleaned Bangalore housing data
- **Input Features**: `location`, `total_sqft`, `bath`, `bhk`

---

## 🗂️ Project Structure

house-price-predictor/
│
├── app.py # Main Flask app
├── Cleaned_data.csv # Cleaned dataset used for prediction
├── RidgeModel.pkl # Trained Ridge Regression model (pickle)
├── templates/
│ └── index.html # Main HTML file with Bootstrap + AJAX
├── static/ # (Optional) For static files like CSS/JS
└── README.md # Project documentation

---

## 🛠️ How to Run

### Prerequisites

- Python 3.7+
- Install required packages:

```bash
pip install flask pandas scikit-learn numpy
