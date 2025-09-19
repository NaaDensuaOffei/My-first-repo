# Student Performance Prediction Model 🎓📊

This project uses logistic regression to predict whether a student passes mathematics based on their reading and writing scores. Built in Google Colab with Python, it demonstrates key skills in data preprocessing, feature selection, model training, and evaluation.

# Project Overview
Dataset: Students Performance dataset

Goal: Predict if a student passes math (score ≥ 60).

Features: Reading score, Writing score

Target: Pass (1 = Yes, 0 = No)

# 🛠️ Tools & Libraries
Python (pandas, numpy, scikit-learn)

Matplotlib / Seaborn for data visualization

Logistic Regression for prediction

Google Colab for development

# Key Steps
Data Preprocessing: Created a binary "pass" column (1 if math ≥ 60, else 0) and selected relevant features (reading & writing scores).

Model Training: Split the data into an 80/20 train-test set and trained the logistic regression model.

Evaluation: Calculated the accuracy score on the test set, generated a confusion matrix, and interpreted coefficients to understand feature importance.

# Results
The model achieved strong predictive accuracy using only reading and writing as predictors. The analysis identified a clear correlation: higher reading and writing scores significantly improve a student's chance of passing math.

---

### 📂 How to Use

You can explore the notebook directly in your browser or clone the repository to run it locally.

* **Open in Google Colab:** [Student Performance Notebook](https://colab.research.google.com/drive/1Y8s-7ID4i3F1sGzmkaPM-MeEXlitfpXh?usp=sharing)
* **Clone the Repository:**
    ```bash
    git clone https://github.com/NaaDensuaOffei/Student-Performance-Analysis.git
    ```

---

### 👩‍💻 Author

**Mabel Naa Densua Offei** | [LinkedIn](https://www.linkedin.com/in/naa-densua/)
