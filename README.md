# Predictive Maintenance of Industrial Machinery Using Machine Learning

This project builds a machine learning model to predict specific types of industrial machine failures—such as tool wear, heat dissipation, or power failure—before they occur. The goal is to reduce unplanned downtime and improve operational efficiency through predictive maintenance.

## 📊 Problem Statement
Industrial machines often fail unexpectedly, leading to significant losses. This project uses historical sensor data to develop a classification model that predicts the exact failure type in advance.

## 🔧 Tech Stack
- Python
- Scikit-learn
- XGBoost
- Pandas, Matplotlib
- Flask (for deployment)
- IBM Cloud Lite (for hosting)

## 📁 Dataset
[Kaggle Dataset](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)

## ⚙️ Features Used
- Air Temperature
- Process Temperature
- Rotational Speed
- Torque
- Tool Wear
- Machine Type

## 🧠 Model
- XGBoost Classifier
- Accuracy: ~90%
- Multi-class classification (Failure Type as target)

## 🚀 Deployment
The trained model is served using Flask and can be deployed on IBM Cloud Lite.

## 📎 Report
Final Project Report (PPT converted to PDF) is available in this repository.

## 📸 Screenshots
_Add screenshots of your app or model output here if available_

## 🧪 Usage
```bash
git clone https://github.com/your-username/predictive-maintenance-ml.git
cd predictive-maintenance-ml
pip install -r requirements.txt
python app/app.py

