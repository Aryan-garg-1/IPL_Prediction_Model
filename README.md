# 🏏 IPL Match Winner Prediction using Machine Learning

An end-to-end Machine Learning project that predicts the winning probability of an IPL cricket match using historical IPL data, player statistics, venue performance, team form, and engineered squad features.

The project demonstrates the complete ML workflow—from data preprocessing and feature engineering to model training, evaluation, and deployment through a Streamlit web application.

---

# 📌 Project Overview

Predicting the outcome of a T20 cricket match is challenging due to the dynamic nature of the game. This project leverages historical IPL data and machine learning to estimate the probability of either team winning before the match begins.

Unlike simple team-based prediction models, this project incorporates player-level statistics, venue history, and team-specific performance metrics to create a more informative prediction pipeline.

---

# 🎯 Objectives

- Predict the probability of Team 1 or Team 2 winning.
- Engineer meaningful cricket-specific features.
- Compare multiple machine learning algorithms.
- Evaluate models using multiple performance metrics.
- Deploy the trained model as an interactive Streamlit application.

---

# 📊 Dataset

The project uses historical IPL ball-by-ball and match datasets.

The datasets include:

- Ball-by-ball records
- Match information
- Player statistics
- Venue information
- Team performances
- Toss details
- Match results

---

# 🛠️ Feature Engineering

One of the major focuses of this project is domain-specific feature engineering.

Features include:

### Batting Features

- Average runs
- Strike rate
- Batting average
- Recent batting performance
- Squad batting strength

### Bowling Features

- Economy rate
- Bowling average
- Wickets per match
- Squad bowling strength

### Team Features

- Historical win percentage
- Team form
- Head-to-head performance
- Team consistency

### Venue Features

- Venue win rate
- Venue scoring trends
- Home advantage

### Squad-Level Features

- Aggregated batting quality
- Aggregated bowling quality
- Team experience
- Overall squad strength

---

# 🤖 Machine Learning Pipeline

The notebook follows a complete end-to-end machine learning workflow.

1. Data Loading
2. Data Cleaning
3. Feature Engineering
4. Exploratory Data Analysis
5. Feature Selection
6. Model Training
7. Cross Validation
8. Model Comparison
9. Model Evaluation
10. Prediction Pipeline
11. Model Serialization
12. Streamlit Deployment

---

# 📈 Models Evaluated

The following algorithms were trained and compared:

- Logistic Regression
- Random Forest
- Gradient Boosting
- LightGBM
- CatBoost

After evaluation, the best-performing model was selected for deployment.

---

# 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- ROC-AUC
- Log Loss
- F1 Score
- Precision
- Recall
- Confusion Matrix
- ROC Curve
- Calibration Curve
- Cross Validation

---

# 💻 Streamlit Application

A complete web application was built using **Streamlit** that allows users to:

- Select Team 1
- Select Team 2
- Choose Match Venue
- Enter Toss Winner
- Select Toss Decision
- Predict Match Winner
- View Winning Probabilities

### Live App

https://iplprediction711.streamlit.app/

### Application Repository

https://github.com/Aryan-garg-1/IPL_Prediction

---

# 📂 Repository Structure

```
├── data/
│   ├── IPL.csv
│   ├── matches.csv
│
├── models/
│   ├── trained_model.pkl
│
├── notebooks/
│   ├── IPL_Predictor.ipynb
│
├── outputs/
│   ├── figures
│   ├── evaluation plots
│
├── requirements.txt
├── README.md
```

---

# 📷 Sample Workflow

```
Historical IPL Data
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Model Training
        │
        ▼
Cross Validation
        │
        ▼
Model Evaluation
        │
        ▼
Model Serialization
        │
        ▼
Streamlit Deployment
```

---

# 🏆 Key Highlights

✅ End-to-End Machine Learning Project

✅ Domain-Specific Feature Engineering

✅ Multiple ML Models Compared

✅ Cross Validation

✅ Comprehensive Model Evaluation

✅ Real-Time Prediction Pipeline

✅ Interactive Streamlit Application

✅ Deployment Ready

---

# 📚 Technologies Used

### Programming

- Python

### Data Analysis

- Pandas
- NumPy

### Visualization

- Matplotlib
- Seaborn

### Machine Learning

- Scikit-learn
- LightGBM
- CatBoost

### Deployment

- Streamlit

### Model Serialization

- Pickle

---

# 🚀 Future Improvements

Some planned improvements include:

- Live player availability updates
- Dynamic playing XI input
- Recent form weighting
- Weather integration
- Pitch report integration
- Hyperparameter optimization
- SHAP-based model explainability
- Ensemble learning

---

# 🎓 Learning Outcomes

This project demonstrates practical experience in:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Machine Learning
- Model Evaluation
- Cross Validation
- Deployment
- Building Interactive ML Applications

---

# 👨‍💻 Author

**Aryan Garg**

Machine Learning | Data Science | AI

GitHub: https://github.com/Aryan-garg-1

---

# ⭐ If you found this project useful, consider giving it a Star!
