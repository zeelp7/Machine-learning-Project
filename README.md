# Food Delivery Time Prediction - DATASCI 3ML3 Final Project

Welcome to my final project for the DATASCI 3ML3 course at McMaster University! This project uses machine learning models to predict food delivery time based on real-world delivery data, including distances, traffic types, delivery person ratings, and more.

---

## 📊 Project Overview

The main objective is to build regression models that can accurately predict the time taken to deliver food orders using a variety of features, including:

- Delivery person's age and ratings
- Restaurant and delivery location coordinates
- Type of order and vehicle used
- Calculated distance (in miles) between pickup and drop-off

---

## 🛠️ Tech Stack & Tools

- Python
- Pandas, NumPy, Scikit-learn
- TensorFlow / Keras
- Geopy for distance calculation
- Matplotlib for visualizations

---

## 🧪 ML Models Implemented

1. **Decision Tree Regressor**
   - Tuned with different tree depths
2. **Gradient Boosting Regressor**
   - Evaluated over various depths for optimization
3. **Neural Networks**
   - Small model using a single hidden layer
   - Larger deep network
   - Regularized neural network with Dropout & L2 Regularization
4. **Ensemble (Bagging)**
   - Combined predictions from multiple models

---

## 📈 Results Summary

- **Best Performing Model:** Neural Network with Regularization
- **Lowest Test MSE:** ~0.0331 (achieved by NN with deeper layers)
- Feature scaling and one-hot encoding significantly improved model accuracy.
- Calculated distances using geopy (Vincenty/Geodesic) greatly enhanced prediction quality.

---

## 📁 Files Included

- `FoodDeliveryPrediction.ipynb` – Complete Jupyter notebook with preprocessing, EDA, model building, tuning, and evaluation.
- `README.md` – This file you're reading.

---

## 📌 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/food-delivery-prediction.git
cd food-delivery-prediction

# Open the notebook
jupyter notebook FoodDeliveryPrediction.ipynb
