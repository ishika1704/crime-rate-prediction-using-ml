Crime Rate Prediction Using Machine Learning for IPC Crime Analysis in India

This project analyzes and predicts crime rates in India using machine learning techniques.
It performs data preprocessing, visualization, feature reduction using PCA, and applies multiple regression models to identify the best-performing algorithm for crime prediction.

---

 1) Project Objectives
- Analyze crime patterns across Indian States/UTs  
- Visualize crime distribution and trends  
- Reduce dimensionality using PCA  
- Compare multiple ML regression models  
- Predict Total IPC Crimes with best accuracy  

---

2) Dataset Used
- **newtrial - Sheet 1 - 01_District_wise_crim 2.csv**
- Contains crime statistics across:
  - 35+ States/UTs  
  - 16+ crime categories  
  - Years 2001–2012  

---

3) Data Preprocessing
- Cleaned column names  
- Removed non-required attributes  
- Filtered only major crime categories  
- Handled missing/invalid entries  
- Performed **feature scaling** before PCA  

---

4) Machine Learning Models Used:

- Linear Regression – Baseline regression model  
- Decision Tree Regressor – Non-linear modeling  
- Random Forest Regressor – Ensemble-based learning  
- KNN Regressor – Distance-based regression  
- SVM (Linear, Polynomial, RBF, Sigmoid Kernels) – Kernel-based approaches  
- XGBoost Regressor – Best-performing boosting model  
- PCA – Used for dimensionality reduction 
---

 5) Best Model  
XGBoost Regressor
- Achieved highest R² score of 0.9768  
- Lowest RMSE and MAE among tested models 
- Best overall prediction performance for IPC crime forecasting

---

 6) Visualizations: 

   a. Project Workflow
![Flowchart](Flowchart.png)

---

   b. Line Plot — Total IPC Crimes per Year
Shows year-wise rising trend in crime.  
![Graph1](Graph1.png)

---

  c. Top 10 States/UTs by Crime Count
Visualizes states with highest crime burden.  
![Graph2](Graph2.png)

---

  d. Correlation Heatmap of Crime Types
Shows which crimes are highly correlated with overall total crimes.  
![Graph3](Graph3.png)

---

  e. Combined Model Performance Table / Additional Graph
Any extra graph generated during analysis.  
![Graph4](Graph4.png)

---

 7) Project Notebook:
     
[**crime_prediction.ipynb**](crime_prediction.ipynb)

Includes:
- Data preprocessing  
- PCA implementation  
- Machine learning models  
- Evaluation metrics  
- Data visualizations  

 ---

8) Project Report:

 [**Report.pdf**](Report.pdf)

---

9) Team Members: Ishika Patni, Palak Tyagi



