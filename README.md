# Intelligent First-Aid & Medical Assistance System 🏥🤖

## Project Overview
This project implements a Machine Learning–based healthcare decision support system that predicts patient condition severity and recommends appropriate medical action.

The system:
- Classifies patient severity as Mild, Moderate, or Severe
- Provides first-aid guidance
- Recommends doctor visits or emergency hospital care
- Identifies nearby hospitals using geolocation (Germany-based routing)

⚠️ This system is a decision-support tool and does not diagnose diseases.

---

## Objectives
- Perform exploratory data analysis (EDA)
- Build and compare multiple ML models
- Classify patient severity levels
- Provide severity-based healthcare recommendations
- Demonstrate a complete ML pipeline

---

## Dataset Information
- 2000 simulated patient records
- Structured healthcare dataset
- Features include:
  - Age, Gender
  - Symptoms (3 per patient)
  - Heart Rate
  - Body Temperature
  - Blood Pressure (Systolic/Diastolic)
  - Oxygen Saturation
- Target Variable:
  - Severity (Mild / Moderate / Severe)

---

## Technologies & Libraries Used
- Python (3.9+)
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Geopy
- OSMnx
- GeoPandas
- Jupyter Notebook

---

## Machine Learning Approach

### Problem Type:
Multi-class Classification

### Models Used:
- Logistic Regression (Baseline Model)
- Random Forest Classifier
- Gradient Boosting Classifier
- Neural Network (MLP Classifier)

### Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1-Score

Best Performing Models:
Random Forest & Gradient Boosting

---

## Severity-Based Decision Logic

🟢 Mild  
- First-aid advice  
- Rest and monitoring  

🟡 Moderate  
- Doctor visit recommended  
- Nearby clinic suggestions  

🔴 Severe  
- Emergency case  
- Nearest hospital recommendation  

Hospital routing is performed using OpenStreetMap data and geodesic distance calculations.

---

## How to Run the Project

1. Place the following files in the same folder:
   - Final_project_code.ipynb
   - medical_dataset.csv

2. Install required libraries:
