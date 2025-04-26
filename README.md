# Flight Price Prediction: End-to-End Machine Learning Project using AWS Sagemaker

## Overview
This project predicts flight prices using machine learning. It includes data processing, model training with AWS SageMaker, and a deployed Streamlit web application.

[Website Link](URL "https://awssagemaker-flightpriceprediction-9dlbstbmrwg3yljvlouwxj.streamlit.app/")

## File Structure
.
├── data/
│   ├── .DS_Store
│   ├── flight_price.csv
│   ├── test.csv
│   ├── train.csv
│   ├── val.csv
├── notebooks/
│   ├── EDA.ipynb
│   ├── data-cleaning.ipynb
│   ├── eda_helper_functions.py
│   ├── feature_engineering.ipynb
│   ├── model-training.ipynb
├── .gitignore
├── app.py
├── preprocessor.joblib
├── requirements.txt
├── train.csv
├── xgboost-model-2

## Notebooks Description
- EDA.ipynb: Exploratory data analysis
- data-cleaning.ipynb: Data preprocessing
- feature_engineering.ipynb: Feature creation
- model-training.ipynb: Model development

## Installation
1. Clone the repository:
git clone https://github.com/yourusername/your-repo.git

2. Install dependencies:
pip install -r requirements.txt

## Running the Application
streamlit run app.py

## AWS SageMaker Details
- Instance: ml.m5.xlarge
- Algorithm: XGBoost
- Training Time: XX minutes
- Accuracy: XX%

## Deployment
The application is deployed on Streamlit Cloud:
https://your-app-name.streamlit.app/

## Future Work
- Add real-time price APIs
- Include more airlines/routes
- Implement user accounts
- Add price trend visualizations

## Contact
Your Name - your.email@example.com
