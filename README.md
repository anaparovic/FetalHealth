# Fetal Health Classification

A machine learning project for classifying fetal health status based on cardiotocography (CTG) measurements.  
The objective is to build and evaluate classification models capable of categorizing fetal health into three clinical classes: **Normal**, **Suspect**, and **Pathological**.

This project was developed as an exploratory and predictive analysis workflow using Python, with a focus on medical data preprocessing, model training, and performance evaluation.

---

## Project Overview

Early identification of potential fetal health problems is essential for supporting medical decision-making and reducing risks for both the mother and the newborn. This project applies supervised machine learning techniques to fetal cardiotocography data in order to classify fetal health conditions based on numerical clinical indicators.

The implemented models include:

- **Random Forest Classifier**
- **Support Vector Machine**
- **XGBoost Classifier**

The models are evaluated using standard classification metrics such as accuracy, precision, recall, F1-score, sensitivity, specificity, and confusion matrices.

---

## Dataset

The dataset used in this project is the **Fetal Health Classification** dataset, available on Kaggle:

[https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification/data](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification/data)

The dataset contains **2,126 observations** and **22 columns**, including cardiotocography-derived features and the target variable `fetal_health`.

The target variable contains three classes:

| Class | Meaning |
|---|---|
| 1 | Normal |
| 2 | Suspect |
| 3 | Pathological |

Main features include fetal heart rate baseline, accelerations, fetal movement, uterine contractions, decelerations, short-term variability, long-term variability, and histogram-based measurements.

---

## Repository Structure

```text
FetalHealth/
│
├── Fetal_health.ipynb   # Main notebook containing data analysis, preprocessing, modeling and evaluation
├── README.md            # Project documentation
```

---

## Technologies Used

The project was developed using the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`

---

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/anaparovic/FetalHealth.git
cd FetalHealth
```

### 2. Install the required dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

### 3. Download the dataset

Download the dataset from Kaggle:

[https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification/data](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification/data)

Place the CSV file in the appropriate directory and update the file path in the notebook if necessary.

### 4. Run the notebook

Open the notebook in Jupyter Notebook, JupyterLab, or Google Colab:

```bash
jupyter notebook Fetal_health.ipynb
```

Then run the cells sequentially.
