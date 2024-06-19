### Credit Card Fraud Detection

Welcome to the Credit Card Fraud Detection project! This repository contains a machine learning project aimed at identifying fraudulent credit card transactions. The project leverages various data analysis and machine learning techniques to build a predictive model capable of distinguishing between legitimate and fraudulent transactions.

---

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
---

## Introduction

Credit card fraud is a significant issue that affects both consumers and financial institutions. This project focuses on building a machine learning model to detect fraudulent transactions from a dataset of anonymized credit card transaction records. The dataset includes transactions labeled as either legitimate or fraudulent.

---

## Dataset

The dataset used in this project is the [Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) provided by Kaggle. It consists of 284,807 transactions made by European cardholders in September 2013. The dataset is highly imbalanced, with the minority class (fraudulent transactions) representing only 0.172% of the data.

- **Features**: The dataset includes 30 features, 28 of which are the result of a PCA transformation for privacy reasons.
- **Classes**: The target variable `Class` indicates whether a transaction is legitimate (0) or fraudulent (1).

---

## Project Structure

```
CreditCardFraudDetection/
│
├── data/
│   └── creditcard.csv           # The dataset (needs to be downloaded separately)
│
├── notebooks/
│   └── fraud_detection.ipynb    # Jupyter Notebook with analysis and model training
│
├── README.md                    # Project readme file
```

---

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/CreditCardFraudDetection.git
    cd CreditCardFraudDetection
    ```

2. **Install Required Packages**:
    Create a virtual environment (optional but recommended) and install the dependencies:
    ```bash
    python -m venv env
    source env/bin/activate       # On Windows use `env\Scripts\activate`
    pip install -r requirements.txt
    ```

3. **Download the Dataset**:
    Download the dataset from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud) and place it in the `data/` directory.

---

## Usage

1. **Data Preprocessing**:
    ```bash
    python src/data_preprocessing.py
    ```

2. **Train and Evaluate the Model**:
    ```bash
    python src/model_training.py
    ```

3. **Generate Visualizations**:
    ```bash
    python src/visualization.py
    ```

4. **Jupyter Notebook**:
    Alternatively, you can explore and run the analysis and model training in the provided Jupyter Notebook:
    ```bash
    jupyter notebook notebooks/fraud_detection.ipynb
    ```

---

## Results

The project includes detailed model performance metrics and visualizations, including:

- **Confusion Matrix**: A visualization of the true vs. predicted labels.
- **ROC-AUC Curve**: Measures the model’s ability to distinguish between classes.
- **Precision-Recall Curve**: Useful for understanding the trade-off between precision and recall.
- **Feature Analysis**: Insights into the importance and distribution of features.


---

Feel free to reach out if you have any questions or suggestions. Happy coding!

---

**GitHub Repository**: [Credit Card Fraud Detection](https://github.com/your-repository-link)
