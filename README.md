# Heart Disease Prediction using Machine Learning

## Project Overview

This project predicts whether a person is likely to have heart disease using Machine Learning classification algorithms. The model is trained using medical and health-related features such as age, blood pressure, cholesterol, heart rate, diabetes history, smoking habits, and more.

The main goal of this project is to compare multiple classification algorithms and identify the best-performing model for accurate heart disease prediction.

---

## Algorithms Used

The following classification algorithms are implemented in this project:

* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree Classifier
* Random Forest Classifier

---

## Dataset Features

The dataset contains the following input features:

* Age
* Blood Pressure
* Cholesterol
* Max Heart Rate
* Exercise Induced Angina
* Oldpeak
* Smoking
* Diabetes

### Target Variable

* Heart Disease

  * 1 = Disease Present
  * 0 = No Disease

---

## Project Workflow

### Step 1: Data Collection

The dataset is stored in CSV format and loaded using Pandas.

### Step 2: Data Preprocessing

* Handling missing values
* Feature selection
* Feature scaling using StandardScaler

### Step 3: Train-Test Split

The dataset is divided into:

* Training Data (80%)
* Testing Data (20%)

### Step 4: Model Training

All four classification models are trained using the training dataset.

### Step 5: Model Evaluation

Performance is measured using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Precision
* Recall
* F1-Score

---

## Results

| Model               | Accuracy         |
| ------------------- | ---------------- |
| Logistic Regression | High             |
| SVM                 | High             |
| Decision Tree       | Medium           |
| Random Forest       | Best Performance |

Random Forest gives the best overall accuracy and performance among all models.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook / Kaggle Notebook

---

## Files Included

* `project-1.ipynb` → Main project notebook
* `heart_disease_dataset.csv` → Dataset file
* `README.md` → Project documentation

---

## Conclusion

This project helps in early prediction of heart disease using machine learning techniques. It can be useful in healthcare systems for assisting doctors and improving patient diagnosis.

Random Forest performed best due to better handling of multiple features and improved prediction accuracy.

---

## Future Scope

* Add larger real-world datasets
* Deploy as a web application
* Use Deep Learning models
* Real-time health prediction dashboard

---

## Author

Harshit Saini

Machine Learning Project for Academic and Placement Purpose
