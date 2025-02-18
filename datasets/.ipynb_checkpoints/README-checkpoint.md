# Earthquake Analysis and Prediction in Turkey (1999–2025)

## **Project Overview**
This project analyzes earthquake data in Turkey from 1999 to 2025 to uncover patterns in seismic activity, explore the relationship between earthquake magnitude and features such as depth and location, and build a predictive model for earthquake magnitudes. The study incorporates data preprocessing, exploratory data analysis (EDA), geospatial mapping, and machine learning techniques to better understand and predict earthquake behavior.

---

## **Objectives**
1. Analyze earthquake trends over time, location, and depth.
2. Visualize earthquake distributions and fault lines using maps.
3. Develop and compare predictive models for earthquake magnitudes.

---

## **Key Features**
- **Data Exploration**: Analysis of earthquake depth, magnitude, and location trends.
- **Geospatial Mapping**: Visualization of earthquake locations and fault lines in Turkey.
- **Predictive Modeling**: Comparison of machine learning models, including Linear Regression, Random Forest, and XGBoost.
- **Performance Evaluation**: Residual analysis and validation of model performance.

---

## **Data**
- **Source**: Earthquake dataset (1999–2025) containing features like date, time, latitude, longitude, depth, and magnitude.
- **Preprocessing**: Handling missing values, extracting datetime features, and scaling for machine learning.

---

## **Methods**
1. **Data Preprocessing**:
   - Cleaning and transforming the dataset.
   - Extracting features (e.g., year, month, depth).

2. **Exploratory Data Analysis (EDA)**:
   - Trends in earthquake frequency over time.
   - Magnitude distributions and correlation analysis.
   - Depth vs. magnitude relationships.

3. **Machine Learning Models**:
   - Models: Linear Regression, Random Forest, and XGBoost.
   - Performance Metrics: Mean Squared Error (MSE) and R².
   - Best Model: Tuned Random Forest achieved the highest performance (Test R²: 0.5668).

---

## **Requirements**
To run this project, install the following Python libraries:
```bash
pip install pandas numpy matplotlib seaborn basemap xgboost scikit-learn
