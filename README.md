Air Quality Prediction using Machine Learning

This project predicts Air Quality Index (AQI) levels by analyzing pollutant concentrations and meteorological factors using machine learning. It can classify air quality into categories (Good, Moderate, Poor…) or predict exact AQI values.

Features

Uses pollutants such as PM2.5, PM10, NO₂, SO₂, CO, and O₃ as inputs

Supports both classification (AQI category) and regression (AQI value)

Achieves 95%+ accuracy on clean datasets

Preprocessing pipeline with scaling and missing value handling

Visualizes pollutant trends and feature importance

Easy to extend with live data from AQICN API or IoT sensors

Google Colab-ready for quick execution

Tech Stack

Python (Pandas, NumPy, Scikit-learn, Matplotlib)

Machine Learning Models: Random Forest, Gradient Boosting, or SVM

Optional Deployment: Flask/FastAPI + Streamlit/React for web interface

How It Works

Collect historical or real-time air quality data

Preprocess and normalize the dataset

Train ML model to predict AQI or classify categories

Evaluate performance using accuracy, F1-score, and feature importance

Getting Started
# Clone the repository
git clone https://github.com/your-username/air-quality-prediction.git
cd air-quality-prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Air_Quality_Prediction.ipynb
