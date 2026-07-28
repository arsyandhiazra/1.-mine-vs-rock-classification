# Sonar Rock vs Mine Classification

A Machine Learning project to classify sonar signals as **Rock (R)** or **Mine (M)** using Logistic Regression.

---

## Project Overview

This project uses the Sonar dataset to build a binary classification model that predicts whether a sonar signal comes from a rock or a mine.

The project covers the complete machine learning workflow:

- Data loading
- Exploratory Data Analysis (EDA)
- Data preparation
- Train-test split
- Model training
- Model evaluation
- Prediction on new data

---

## Dataset

- **Dataset:** Sonar Dataset
- **Instances:** 208
- **Features:** 60 numerical attributes
- **Target:**
  - R = Rock
  - M = Mine

---

## Model

- Logistic Regression
- Train/Test Split (80/20)

---

## Libraries

- NumPy
- Pandas
- Scikit-Learn

---

## Project Structure

```
mine-vs-rock-classification/
│
├── data/
│   └── sonar_data.csv
│
├── notebooks/
│   └── sonar_rock_vs_mine.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Installation

```bash
git clone https://github.com/arsyandhiazra/1.-mine-vs-rock-classification.git

cd 1.-mine-vs-rock-classification

pip install -r requirements.txt
```

---

## Run the Notebook

Open the notebook using Jupyter Notebook or VS Code and run all cells.

---

## Results

The notebook reports:

- Training Accuracy
- Testing Accuracy
- Prediction on new sonar data

---

## Future Improvements

- Compare multiple machine learning algorithms
- Perform feature engineering
- Hyperparameter tuning
- Build a Streamlit web application
- Deploy the model

---

## Author

Zulfa Arsyandhi Azra
Information Engineering Undergraduate, Universitas Gadjah Mada
