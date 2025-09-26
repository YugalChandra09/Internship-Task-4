# Elevate Labs AI/ML Internship - Task 4: Logistic Regression

## 📝 Objective

[cite_start]This repository contains the solution for **Task 4: Logistic Regression** of the Elevate Labs AI & ML Internship[cite: 1]. [cite_start]The objective of this task is to build and evaluate a binary classification model to predict whether a user will purchase a product based on their age, gender, and estimated salary[cite: 1].

---

## 📊 Dataset

The project uses the **Social Network Ads** dataset (`data.csv`) provided for this task. The goal is to predict the 'Purchased' column, which indicates whether a user made a purchase (1) or not (0).

---

## 🛠️ Workflow & Methodology

The project follows a standard machine learning workflow for classification:

* **1. Data Preprocessing**: The dataset was loaded, and the non-essential 'User ID' column was dropped. The categorical 'Gender' feature was converted into a numerical format.
* **2. Feature Scaling**: The numerical features ('Age', 'EstimatedSalary', and encoded 'Gender') were scaled using `StandardScaler`. This standardization ensures that all features contribute equally to the model's performance, preventing features with larger scales from dominating the model.
* **3. Train-Test Split**: The preprocessed data was split into a training set and a testing set to allow for an unbiased evaluation of the model on unseen data.
* **4. [cite_start]Model Training**: A `LogisticRegression` model from the Scikit-learn library was instantiated and fitted on the scaled training data[cite: 1].
* **5. [cite_start]Model Evaluation**: The model's performance was evaluated on the test set using an accuracy score and a confusion matrix to understand its predictive power and the types of errors it makes[cite: 1].

---

## 📈 Evaluation Results

* The model achieved an **Accuracy Score** of **`[Insert your accuracy score, e.g., 0.89]`** on the test data.
* A **Confusion Matrix** was generated to provide a detailed breakdown of the model's predictions, showing the number of True Positives, True Negatives, False Positives, and False Negatives. This gives deeper insight into the model's performance beyond a single accuracy metric.

---

## 💻 Tools and Libraries Used

* Python
* [cite_start]Pandas [cite: 1]
* [cite_start]Scikit-learn [cite: 1]
* [cite_start]Matplotlib & Seaborn [cite: 1]

---

## 🚀 How to Run

1.  Clone this repository to your local machine.
2.  Ensure you have Python and the required libraries installed.
3.  Open and run the Jupyter Notebook (`.ipynb`) file to see the complete implementation and results.
