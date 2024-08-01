# Credit Fraud Detection System

This repository contains a Jupyter Notebook implementing a credit fraud detection system. The system utilizes machine learning algorithms to identify potential fraudulent transactions based on a dataset of credit card transactions.

## Table of Contents
- [Introduction](#introduction)
- [Setup Instructions](#setup-instructions)
- [Usage Guidelines](#usage-guidelines)
- [Contributing](#contributing)

## Introduction

Credit card fraud is a significant issue in the financial industry, resulting in substantial financial losses each year. This project aims to build a credit fraud detection system using machine learning techniques to help mitigate this issue. The system is designed to analyze credit card transactions and identify potentially fraudulent ones.

## Setup Instructions

To set up the project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/YASSINEKS007/Credit-Card-Fraud-Detection-System.git
    ```

2. **Create a virtual environment and activate it:**

    ```bash
    virtualenv venv 
    venv\Scripts\activate   # On Mac, use `source venv/bin/activate`
    ```

3. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```
4. **Download the dataset:**

    Create a folder named data and download the dataset from kaggle. The dataset link: [https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data)

5. **Open the `main.ipynb` notebook:**

    In your web browser, navigate to `main.ipynb` and open it, or use vscode jupyter notebook to start exploring the project.

## Usage Guidelines

The Jupyter Notebook `main.ipynb` contains all the code and explanations necessary to understand and run the credit fraud detection system. The following steps outline the general workflow:

1. **Data Loading and Exploration:**
   - Load the dataset and perform exploratory data analysis (EDA) to understand the data distribution and characteristics.


2. **Data Preprocessing:**
   - Perform Data cleaning operations.
   - Scale the data.

3. **Model Building:**
   - Split the data into training and testing sets.
   - Train machine learning models, the models used in this project are : Logistic Regression, Random Forest, Decision Tree, Gradient Boosting, Naive Bayes, KNN and Support Vector Classifier.


4. **Model Evaluation:**
   - Assess the models' performance on the test set.
   - Analyze the results and select the best-performing model.

5. **Conclusion:**
   - Summarize the findings and results of the project.
   - Discuss potential improvements and future work.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.


