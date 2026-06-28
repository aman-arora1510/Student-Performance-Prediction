# BCA Student Performance Prediction

This repository contains a **Machine Learning** project built with **Python** to predict a student's performance index based on various academic and lifestyle factors. 

## 📊 Dataset Features
The model analyzes the following features to make predictions:
* **Hours Studied**: The number of hours a student spent studying.
* **Previous Score**: The student's score in previous examinations.
* **Extracurricular Activities**: Whether the student participates in extracurricular activities (binary: Yes/No or 1/0).
* **Sleep Hours**: The number of sleep hours the student gets daily.
* **Sample Question Papers Practiced**: The number of sample papers solved.
* **Performance Index**: The target variable (ranging from 10 to 100) representing the student's overall performance.

---

## 🛠️ Tech Stack & Libraries
* **Language**: Python 🐍
* **Machine Learning**: `scikit-learn`
* **Data Manipulation**: `pandas`, `numpy`
* **Data Visualization**: `matplotlib`, `seaborn`

---

## 🤖 Machine Learning Models Implemented
We implemented and compared multiple machine learning models to identify the best predictor:
1. **Linear Regression**: A regression model to find linear relationships between study parameters and student performance.
2. **Decision Tree (Regressor & Classifier)**: Used to capture non-linear patterns and evaluate performance category classification.
3. **Random Forest Regressor**: An ensemble learning method to improve prediction accuracy and reduce overfitting.

---

## 📁 Repository Structure
* **[Student Performance.ipynb](file:///c:/Users/Welcome/Desktop/BCA%20Student%20Performace%20Prediction%20Project/Student%20Performance.ipynb)**: The main Jupyter notebook containing data preprocessing, exploratory data analysis (EDA), model training, evaluation, and visualizations.
* **[Student_Performance.xlsx](file:///c:/Users/Welcome/Desktop/BCA%20Student%20Performace%20Prediction%20Project/Student_Performance.xlsx)**: Dataset containing student performance records.
* **[VAM PRESENTATION.pdf](file:///c:/Users/Welcome/Desktop/BCA%20Student%20Performace%20Prediction%20Project/VAM%20PRESENTATION.pdf)**: Project presentation.
* **[VAM_Project Aman.docx](file:///c:/Users/Welcome/Desktop/BCA%20Student%20Performace%20Prediction%20Project/VAM_Project%20Aman.docx)**: Project report document.


---

## 🚀 How to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/aman-arora1510/Student-Performance-Prediction.git
   cd Student-Performance-Prediction
   ```

2. **Install the required libraries**:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn openpyxl notebook
   ```

3. **Launch the Jupyter Notebook**:
   ```bash
   jupyter notebook "Student Performance.ipynb"
   ```
