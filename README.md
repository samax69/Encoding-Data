# Encoding-Data
Ordinal Encoder &amp; Nominal Encoder

# Data Encoding & Preprocessing Project 

This is a small project where I worked on preprocessing a medical dataset to make it ready for machine learning. It mainly focuses on handling categorical features using different encoding techniques like Label Encoding, One-Hot Encoding, and Ordinal Encoding.

---

## What This Project Does

- Reads in a real-world Excel dataset (`dataforEncoding.xls`)
- Cleans missing values and irrelevant features
- Applies different encoding methods depending on the feature type
- Uses custom order for Ordinal Encoding (e.g., for cholesterol levels)
- Visualizes some of the distributions
- Outputs a final cleaned dataset that’s ready to be used in any ML model

---

## Files

- `project.ipynb`: The main notebook where everything happens — preprocessing, visualization, encoding
- `dataforEncoding.xls`: The original raw dataset

---

##  Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `openpyxl` (for reading Excel files)

---

##  Why I Did This

I wanted to get more hands-on experience with data preprocessing — which is a super important part of any ML pipeline. This project helped me understand:
- When to use which encoder
- How to deal with missing values
- How to handle categorical features with logical orderings

---

##  How to Run It

1. Clone the repo  
   `git clone https://github.com/your-username/your-repo-name.git`

2. Install the requirements  
   `pip install -r requirements.txt`

3. Run the notebook  
   `jupyter notebook project.ipynb`

---

##  To-Do / Improvements

- Add train-test split and run a basic ML model
- Explore feature scaling
- Make encoding steps reusable via functions or a pipeline

---

##  Feel free to fork this repo or reach out if you have any suggestions or questions!

