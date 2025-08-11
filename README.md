 Decision Trees & Random Forest

 Objective
To build and evaluate **Decision Tree** and **Random Forest** models for classifying whether a person has heart disease using the **Heart Disease Dataset**.

---

Dataset
The dataset contains medical attributes such as age, cholesterol, resting blood pressure, and others to predict the presence of heart disease.

Source: [Heart Disease Dataset (UCI)](https://www.kaggle.com/ronitf/heart-disease-uci)  
In this notebook, we use a hosted CSV from Plotly's GitHub.

---

 Steps Performed
1. **Data Loading** – Loaded the dataset into a Pandas DataFrame.
2. **Data Preprocessing** – Split into features (X) and target (y).
3. **Train/Test Split** – 80% training, 20% testing.
4. **Model Building** – Implemented `DecisionTreeClassifier` and `RandomForestClassifier`.
5. **Model Evaluation** – Accuracy score, confusion matrix, classification report.
6. **Feature Importance** – Identified most important features in predictions.
7. **Visualization** – Plotted Decision Tree and Feature Importance bar chart.
8. **Cross-Validation** – Verified stability using 5-fold cross-validation.

---

 Results
- **Decision Tree Accuracy**: ~82%  
- **Random Forest Accuracy**: ~87%  
- **Top Features**: `cp` (chest pain type), `thalach` (max heart rate), `ca` (number of vessels colored), `oldpeak` (ST depression)  

---

 Sample Output
Confusion Matrix (Decision Tree):  
![Decision Tree Confusion Matrix](confusion_matrix_dt.png)  

Feature Importance (Random Forest):  
![Random Forest Feature Importance](feature_importance.png)  
