<h1>Data Science & Analysis Projects</h1>

This repository contains a collection of Jupyter Notebooks covering different aspects of data analysis, machine learning, and data preprocessing. Each notebook focuses on a unique dataset and analytical approach, ranging from exploratory data analysis to predictive modeling and recommendation systems.


<h2>Getting Started</h2>

To run any notebook in this repository:

1. Clone this repository:
```bash
git clone https://github.com/KugleBlitz007/CSI4142.git
cd CSI4142
```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open the desired `.ipynb` file and run all cells **in order**.

Some notebooks automatically load datasets from this GitHub repo. For others, links to the dataset sources are provided.


<h1>Project Files</h1>

### 1. Mobile Device Usage and User Behavior

Analyzes screen time, app usage, battery, and data consumption to classify user behavior and detect patterns. Useful for app developers, phone makers, and data scientists building predictive models.

* [Dataset](https://github.com/KugleBlitz007/CSI4142/blob/main/user_behavior_dataset.csv)

---

### 2. Customer Segmentation

Performs EDA on the **Adult Census Income dataset** to study how socio-economic and demographic factors influence income. Helps identify income disparities and segmentation patterns.

* [Dataset Info](http://www.census.gov/ftp/pub/DES/www/welcome.html)

---

### 3. Home Loan Approval

Predicts loan eligibility based on customer details using classification models. The dataset contains demographic and financial attributes of applicants.

* [Dataset](https://github.com/KugleBlitz007/CSI4142/blob/main/loan_sanction_train.csv)

---

### 4. Predictive Analysis – Regression & Classification

Uses **Medical Cost Personal Dataset** to build linear regression models predicting insurance charges. Includes outlier detection with Local Outlier Factor (LOF) and feature engineering steps.

---

### 5. Clean Data Checker

A custom tool for identifying invalid data, duplicates, and missing values. Implements imputation techniques and generates structured reports.

* Dataset: **Movies dataset (IMDB Netflix titles)** for feature extraction and recommendation experiments.

---

### 6. Heart Attack Risk & Prediction (India)

Evaluates imputation techniques on a dataset of cardiovascular risk factors. Helps improve predictive models for early detection of heart disease in India.

* [Dataset](https://github.com/KugleBlitz007/CSI4142/blob/main/heart_attack_prediction_india.csv)

---

### 7. Anime Recomendation Part 1 and Part 2

Applies similarity measures and builds a **content-based recommendation system** using an anime dataset. Includes data cleaning, imputation, and clustering.

* Dataset shape: 12,294 rows × 8 features

---

##  Requirements

* Python 3.8+
* Jupyter Notebook
* pandas, numpy, matplotlib, seaborn, scikit-learn, (and other ML libraries as used in each notebook)

You can install all dependencies at once using:

```bash
pip install -r requirements.txt
```
