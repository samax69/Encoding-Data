# Encoding-Data
Ordinal Encoder &amp; Nominal Encoder

# Customer Data Preprocessing and Encoding Project

This project demonstrates preprocessing and encoding techniques on a customer dataset using Python and popular data science libraries like `pandas`, `scikit-learn`, and `matplotlib`.

## 🔍 Project Description

This notebook handles real-world categorical and numerical data from an Excel file. It focuses on:
- Cleaning missing values
- Label encoding and one-hot encoding
- Ordinal encoding with custom order
- Exploratory Data Analysis (EDA)
- Preparing the dataset for machine learning models

## 📁 Files

- `project.ipynb`: The main Jupyter Notebook containing all preprocessing, visualization, and encoding steps.
- `dataforEncoding.xls`: The input dataset containing customer-related information (gender, age, cholesterol, etc.).

## 🧠 Key Features

- Categorical encoding (Label, One-hot, Ordinal)
- Visualization of distributions and encoded features
- Handling missing values
- Ready-to-use feature matrix `X` and label vector `y` for ML tasks

## 📊 Dataset Overview

The dataset includes:
- Categorical variables like Gender, Cholesterol, Glucose, Smoking
- Numerical variables like Age, Height, Weight
- Target variable indicating medical outcome or risk group

## ⚙️ How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. Install dependencies:
    ```bash
    pip install pandas numpy matplotlib scikit-learn
    ```

3. Launch the notebook:
    ```bash
    jupyter notebook project.ipynb
    ```

## 📦 Dependencies

- Python 3.8+
- pandas
- numpy
- matplotlib
- scikit-learn
- openpyxl (for `.xls` or `.xlsx` file reading)

Install with:
```bash
pip install -r requirements.txt
