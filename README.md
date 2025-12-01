# Student Performance Prediction

**Author:** Diallo Souleymana

This project demonstrates how to predict **student performance** using **Multiple Linear Regression** in Python. The model uses academic and lifestyle factors to estimate a student’s **Performance Index**.

---

## Project Overview

**Objective:**  
Predict a student’s performance based on study habits, previous scores, sleep hours, extracurricular activities, and practice question papers.

**Dataset Features:**
- `Hours Studied` (numeric) – Number of hours a student studies
- `Previous Scores` (numeric) – Student's past academic scores
- `Extracurricular Activities` (categorical: Yes/No) – Participation in activities
- `Sleep Hours` (numeric) – Average hours of sleep per day
- `Sample Question Papers Practiced` (numeric) – Number of practice papers attempted
- `Performance Index` (numeric) – Target variable

---

## Methodology

1. **Data Preprocessing**
   - Encode categorical variables
   - Handle missing values (if any)
   - Scale numerical features

2. **Exploratory Data Analysis (EDA)**
   - Histograms, boxplots, and scatterplots
   - Correlation heatmap and pairplots

3. **Model Training**
   - Split data into `X_train`, `X_test`, `y_train`, `y_test`
   - Train a Multiple Linear Regression model
   - Predict performance on test data

4. **Evaluation**
   - Metrics: Mean Squared Error (MSE), R² Score
   - Residual analysis

---

## Technologies Used

- Python 3
- pandas, numpy
- scikit-learn
- seaborn, matplotlib
- Jupyter Notebook

---

## Usage

1. Clone the repository:

```bash
git clone https://github.com/diallisouleyman78-droid/Student-performance.git
