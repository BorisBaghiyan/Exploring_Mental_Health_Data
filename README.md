# 🧠 Exploring Mental Health Data — Classification Project

This project focuses on predicting depression levels based on lifestyle, academic/work pressure, and psychological factors.  
Built for the Kaggle competition "Playground Series - Season 4, Episode 11", the project uses machine learning to classify individuals based on mental health indicators.

---

## 📌 Project Overview

The dataset contains features related to:
- Academic or work stress  
- Sleep patterns, hobbies, health habits  
- Social life and emotional stability  
- Target column: Depression (classification label)

The goal is to analyze these factors and build a classification model that can predict depression presence or severity with high accuracy.

---

## 📁 Repository Structure

- mental_health_rf_classifier.ipynb — main notebook for preprocessing, modeling, and prediction  
- train.csv — labeled training data  
- test.csv — test data without labels  
- submission.csv — final predictions for Kaggle  
- README.md — project description

---

## 🚀 Installation

1. Clone the repository:
```
git clone https://github.com/BorisBaghiyan/Exploring_Mental_Health_Data.git
```
2. Navigate to the project directory:
```
cd Exploring_Mental_Health_Data
```
3. (Optional) Set up a virtual enviroment
```
python -m venv venv
venv\Scripts\activate
```
4. Install dependencies
```
pip install -r requirements.txt
```

## 🧪 How to Use
1. Open the mental_health_rf_classifier.ipynb notebook in Jupyter or Google Colab:

2. Run all cells step-by-step to:
   
   .Load and clean the data
   
   .Encode categorical features
   
   .Train a classification model
   
   .Generate predictions and save submission.csv

3.Submit the file to Kaggle if participating

## 📊 Notes
 .The project uses Random Forest classifier as baseline

 .Handles object column encoding safely with LabelEncoder

 .Aims for a clean, reproducible pipeline ready for experimentation and tuning
