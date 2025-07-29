# 📊 Student Habits and Performance Analysis

This project explores how various lifestyle and academic habits affect students' academic performance using data analysis and linear regression modeling.
 The dataset contains information about students' study habits, sleep patterns, social media usage, and more.

---

## 🧠 Project Objective

To analyze the influence of students’ daily routines — including study hours, sleep, internet quality, and 
social media usage — on their exam performance and to build a regression model that predicts exam scores.

---

## 🗃️ Dataset

"student_habits_performance.csv"
- Features include:
  - Age
  - Gender
  - Study hours per day
  - Sleep hours
  - Social media hours
  - Netflix hours
  - Attendance percentage
  - Mental health rating
  - Diet quality
  - Parental education level
  - Internet quality
  - Participation in extracurricular activities
  - Part-time job
  - Exam score (target)


## ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn


## 📌 Steps Performed

### 1. Data Loading & Inspection
- Loaded CSV file
- Checked for null values, duplicates
- Inspected data types and distribution

### 2. Data Preprocessing
- Handled categorical variables using:
  - 'OrdinalEncoder' for ordinal features
  - 'OneHotEncoder' for nominal features
- Scaled numerical features using 'StandardScaler'

### 3. Exploratory Data Analysis (EDA)
- Distribution plots (histograms, KDE)
- Count plots and bar charts for categorical variables
- Correlation heatmap
- Scatter plots, pairplots, violin plots, and jointplots

### 4. Modeling
- Split data into train/test sets
- Trained a **Linear Regression** model
- Evaluated with:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² score


## 📈 Model Evaluation

| Metric | Value |
|--------|-------|
| MSE    | 2.1305555328209086e-29|
| RMSE  | 4.615794116748394e-15|
| MAE   | 2.6716406864579767e-15|
| R² Score |1.0|


## 🔍 Key Insights

- Higher study hours positively correlate with exam scores.
- Poor sleep or high social media usage can negatively impact performance.
- Good internet quality and regular attendance support higher scores.
- Balanced diet and mental health are also associated with better academic results.

THANK YOU!!

