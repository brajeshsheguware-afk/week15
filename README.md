# STUDENT EXAM PASS PREDICTION SYSTEM USING LOGISTIC REGRESSION

## PROJECT OVERVIEW

The **Student Exam Pass Prediction System** is a Machine Learning and Data Analytics project developed to analyze student academic performance and predict whether a student is likely to **Pass** or **Fail** in examinations.

Educational institutions generate large amounts of student-related data such as study hours, attendance records, previous exam scores, parental education levels, internet accessibility, and extracurricular participation. Manually identifying students who are at academic risk is often difficult and inefficient.

This project utilizes **Exploratory Data Analysis (EDA)**, **Logistic Regression**, and **Interactive Dashboard Visualization** to identify factors influencing student success and support data-driven academic decision-making.

---

## PROBLEM STATEMENT

Educational institutions collect extensive student performance data, but identifying students who may fail examinations through manual analysis is challenging and time-consuming.

Students with:

* Low attendance rates
* Limited study hours
* Poor previous academic performance
* Lack of educational support resources

are more likely to struggle academically.

Failure to identify these students early can lead to:

* Increased failure rates
* Poor academic performance
* Delayed interventions
* Reduced student confidence
* Lower institutional outcomes

An automated prediction system can help educators identify at-risk students and provide timely support.

---

## OBJECTIVES

The primary objectives of this project are:

* Perform Exploratory Data Analysis (EDA) on student performance data.
* Analyze factors affecting examination success.
* Identify academic risk categories among students.
* Build a Logistic Regression model for Pass/Fail prediction.
* Evaluate model performance using standard classification metrics.
* Develop interactive dashboards for performance monitoring.
* Generate actionable insights for educational institutions.

---

## DATASET INFORMATION

### Dataset Source

Student Performance Prediction Dataset from Kaggle

Dataset Link:

https://www.kaggle.com/datasets/amrmaree/student-performance-prediction

---

## FEATURES USED

| Feature                    | Description                   |
| -------------------------- | ----------------------------- |
| Student_ID                 | Unique identifier of student  |
| Gender                     | Student gender                |
| Study_Hours_per_Week       | Weekly study hours            |
| Attendance_Rate            | Attendance percentage         |
| Past_Exam_Scores           | Average previous exam score   |
| Parental_Education_Level   | Parents' education level      |
| Internet_Access_at_Home    | Internet availability at home |
| Extracurricular_Activities | Participation in activities   |
| Final_Exam_Score           | Final examination score       |
| Pass_Fail                  | Target variable               |

---

## TECHNOLOGIES USED

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-Learn

### Machine Learning Algorithm

* Logistic Regression

### Dashboard Tools

* Plotly
* Streamlit / Dash

---

## PROJECT WORKFLOW

### 1. Data Collection

* Load dataset from Kaggle
* Explore dataset structure
* Identify numerical and categorical variables

### 2. Data Cleaning & Preprocessing

* Handle missing values
* Remove duplicate records
* Verify data types
* Encode categorical variables
* Remove Student_ID column
* Scale numerical features

### 3. Descriptive Statistics

Calculate:

* Average Study Hours
* Average Attendance Rate
* Average Past Exam Scores
* Average Final Exam Score
* Pass vs Fail Count
* Gender Distribution

---

## STUDENT PERFORMANCE ANALYSIS

The project analyzes:

### Academic Factors

* Study Hours
* Attendance Rate
* Past Exam Scores
* Final Exam Scores

### Student Characteristics

* Gender
* Internet Access
* Parental Education Level
* Extracurricular Participation

The analysis helps identify key indicators of student success and failure.

---

## GROUP-BASED ANALYSIS

The following comparisons are performed:

* Study Hours vs Pass/Fail
* Attendance Rate vs Pass/Fail
* Past Exam Scores vs Pass/Fail
* Gender vs Pass Rate
* Internet Access vs Pass Rate
* Parental Education vs Performance
* Extracurricular Activities vs Pass Rate

---

## RELATIONSHIP ANALYSIS

Correlation and relationship analysis are performed between:

* Study Hours and Final Exam Score
* Attendance Rate and Final Exam Score
* Past Exam Scores and Final Exam Score
* Parental Education and Student Performance
* Internet Access and Academic Achievement

---

## DATA VISUALIZATIONS

### Bar Charts

* Pass vs Fail Distribution
<img width="1771" height="429" alt="image" src="https://github.com/user-attachments/assets/db262b3e-e8ae-44be-bb99-12da69417e0d" />

* Gender Distribution
<img width="1763" height="406" alt="image" src="https://github.com/user-attachments/assets/0fd78191-535b-40e3-a52a-b0a3ba645192" />

* Internet Access Distribution

### Histograms

* Study Hours Distribution
* Attendance Rate Distribution
* Final Exam Score Distribution

### Scatter Plots

* Study Hours vs Final Exam Score
<img width="548" height="379" alt="image" src="https://github.com/user-attachments/assets/367d6d28-ee35-4d55-932f-b2a7b204434b" />

* Attendance vs Final Exam Score
<img width="543" height="379" alt="image" src="https://github.com/user-attachments/assets/0a9b7f6b-bb5a-4a6a-bb0c-d5f75bcd191b" />

<img width="1763" height="423" alt="image" src="https://github.com/user-attachments/assets/73689a71-9b66-4b2d-b221-2b8bbc188ccd" />


### Box Plots

* Final Exam Score Outlier Detection
* Attendance Analysis
<img width="1803" height="412" alt="image" src="https://github.com/user-attachments/assets/88e3a70b-0bf0-4357-a04c-f7dfc1ad5432" />

### Heatmaps

* Correlation Analysis of Numerical Features
<img width="1760" height="413" alt="image" src="https://github.com/user-attachments/assets/614a86a7-1888-49fe-87ae-3af69113479f" />
<img width="1764" height="434" alt="image" src="https://github.com/user-attachments/assets/4ee3a52a-15fe-4294-bbac-da3231f2b984" />

---

## STUDENT RISK ANALYSIS

Students are categorized into risk levels based on academic indicators.

### High Risk

* Attendance below 60%
* Study Hours below 10 per week
* Past Exam Scores below 50

### Medium Risk

* Moderate attendance and performance

### Low Risk

* High attendance
* Strong study habits
* Good academic performance

This classification helps institutions identify students requiring additional support.

---

## MACHINE LEARNING MODEL

### Algorithm

Logistic Regression

### Independent Variables

* Gender
* Study_Hours_per_Week
* Attendance_Rate
* Past_Exam_Scores
* Parental_Education_Level
* Internet_Access_at_Home
* Extracurricular_Activities
* Final_Exam_Score

### Dependent Variable

* Pass_Fail

### Modeling Steps

1. Encode categorical variables
2. Scale numerical features
3. Split data into training and testing sets
4. Train Logistic Regression model
5. Predict Pass/Fail outcomes
6. Calculate passing probabilities

---

## MODEL EVALUATION METRICS

The model is evaluated using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Classification Report
* ROC-AUC Score
* ROC Curve

These metrics measure the effectiveness and reliability of the prediction model.

---

## DASHBOARD FEATURES

The project includes an interactive dashboard with:

### Key Performance Indicators

* Total Students
* Pass Percentage
* Fail Percentage
* Average Attendance
* Average Study Hours

### Interactive Visualizations

* Pass vs Fail Distribution
* Attendance Analysis
* Study Hours Analysis
* Gender-wise Performance
* Internet Access Impact
* Risk Category Distribution
* Correlation Heatmap

### Filters

* Gender Filter
* Attendance Filter
* Study Hours Filter
* Pass/Fail Filter

---

## KEY INSIGHTS

* Attendance is one of the strongest indicators of examination success.
* Students with higher study hours generally achieve better final scores.
* Previous academic performance strongly influences future outcomes.
* Internet access can positively impact student learning and achievement.
* Parental education level contributes to academic performance trends.
* Early identification of at-risk students enables timely intervention.

---

## EXPECTED OUTCOME

The Student Exam Pass Prediction System helps educational institutions:

* Predict student examination outcomes.
* Detect academically at-risk students.
* Improve student success rates.
* Support data-driven educational planning.
* Enhance academic intervention strategies.

By combining EDA, Machine Learning, and Interactive Dashboards, the system provides valuable insights that support student achievement and institutional performance.

---

## AUTHOR

Student Exam Pass Prediction System using Logistic Regression

Machine Learning | Data Analytics | Educational Performance Prediction
