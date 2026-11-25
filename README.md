# Salary & Job-Satisfaction Prediction

<p align="center">
  <img src="assets/salary-job-satisfaction-banner.png" alt="Salary and Job-Satisfaction Prediction" width="100%">
</p>

A machine learning project focused on salary estimation and job-satisfaction classification for data-related positions, using a dataset of 5,892 job postings.

The project explores how job characteristics and company-related attributes can be used to estimate salaries and predict whether a salary is satisfactory.

## Project Overview

This repository contains two Jupyter Notebooks covering two supervised machine learning tasks:

### 1. Salary Estimation — Regression

The first notebook develops a Linear Regression model to estimate salaries for data-related positions.

The analysis considers job-related and company-level information, including job titles, salary estimates, company ratings, and location.

### 2. Salary Satisfaction — Classification

The second notebook investigates whether salaries can be classified as satisfactory or not based on job and company characteristics.

Four classification algorithms are considered:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest

## Dataset

The project uses 5,892 job posting records.

The dataset includes features such as:

- Job Title
- Salary Estimate
- Company Rating
- Location
- Company Size
- Industry
- Sector
- Ownership Type
- Company Revenue

### Data Preparation

The data preparation process includes:

- Cleaning salary ranges and converting salary estimates into numerical values.
- Handling categorical variables.
- Preparing the data for regression and classification tasks.
- Selecting job-related and company-related features for model development.

## Model Performance

### Salary Estimation

| Metric | Model | Result |
|---|---|---|
| Mean Absolute Error (MAE) | Linear Regression | ≈ 23.8 (USD thousands) |

The reported MAE corresponds to an average absolute prediction error of approximately USD 23,800 on the original salary scale.

### Salary Satisfaction Classification

| Metric | Model | Result |
|---|---|---|
| Test Accuracy | Logistic Regression | ≈ 70% |

Logistic Regression achieved approximately 70% test accuracy. KNN, Decision Tree, and Random Forest were also included in the model comparison.

The reported metrics reflect the evaluation results documented for this project.

## Repository Structure

```text
Salary_Prediction_Project/
│
├── assets/
│   └── salary-job-satisfaction-banner.png
│
├── Salary_Prediction.ipynb
├── Salary_Prediction_classification_all.ipynb
├── df.csv
└── README.md
```

## Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Installation

Clone the repository:

```bash
git clone https://github.com/sagharganji/Salary_Prediction_Project.git
```

Navigate to the project directory:

```bash
cd Salary_Prediction_Project
```

Install the required dependencies:

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

## Running the Notebooks

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open either of the following notebooks:

- `Salary_Prediction.ipynb` — Salary estimation using Linear Regression.
- `Salary_Prediction_classification_all.ipynb` — Salary-satisfaction classification.

Make sure `df.csv` remains in the project root directory when running the notebooks.

## Project Information

**Author:** Saghar Ganji

**Field:** Data Science & Machine Learning

**Project Period:** September 2023 – November 2023

**GitHub:** [github.com/sagharganji](https://github.com/sagharganji)

**LinkedIn:** [linkedin.com/in/saghar-ganji](https://www.linkedin.com/in/saghar-ganji/)

---

This project is part of my Data Science and Machine Learning portfolio.
