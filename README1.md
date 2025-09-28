
# Task 1
# Student Well-being and Academic Performance Analysis

## Overview
This project involves analyzing a dataset of student well-being and academic performance. The dataset includes various factors such as study habits, sleep hours, screen time, attendance, extracurricular activities, stress levels, and CGPA. The goal of this analysis is to explore the relationships between these factors and derive meaningful insights that can inform academic and wellness strategies.

## Project Structure

### 1. **Data Exploration**
   - **Loading and Exploring the Dataset**: The first step involved loading the dataset and performing an initial exploration to understand its structure and the types of variables involved.
   - **Identifying Missing Values and Duplicates**: We identified any missing data, duplicate entries, and potential unusual patterns that could skew the analysis.
   
### 2. **Data Preprocessing**
   - **Handling Missing Data**: Missing or incomplete data was handled appropriately (e.g., imputation or removal) to ensure the integrity of the analysis.
   - **Dealing with Inconsistent or Duplicate Records**: Duplicate records and any inconsistencies in the data were corrected to avoid data bias.
   - **Converting Categorical Data**: Categorical variables, such as 'Stress Level' and 'Extracurricular Activities', were converted into a usable format (e.g., encoding).
   - **Ensuring Features Are Ready for Analysis**: The dataset was cleaned, and all features were transformed into a format suitable for analysis.

### 3. **Exploratory Data Analysis (EDA)**
   - **Study, Sleep, Screen Time vs. CGPA**: We explored how the number of hours spent studying, sleeping, and screen time affects the students' CGPA.
   - **Stress Level vs. Academic Performance**: Analyzed how different levels of stress impact students’ academic performance (CGPA).
   - **Extracurricular Activities vs. Academic Performance**: Compared the academic performance of students involved in extracurricular activities to those who were not.

### 4. **Insights**
   - At least five meaningful insights were drawn based on the analysis, supported by appropriate graphs and statistical measures. These insights help in understanding the correlation between student behavior and academic performance.

### 5. **Data Export**
   - The cleaned dataset has been exported for further use and analysis, ensuring that it is in a ready-to-use format for future studies or models.

## Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook for analysis and documentation
- Data Preprocessing, Exploratory Data Analysis, and Visualization







# Task 2
# Student Career Performance – Regression Models

This project analyzes factors influencing students’ academic outcomes and placement readiness.  
It applies **Linear Regression** to predict placement scores and **Logistic Regression** to predict placement outcomes (placed vs. not placed).

---

## Dataset

| Column            | Description                                           |
|------------------|-----------------------------------------------------|
| Student_ID       | Unique identifier for each student                  |
| Hours_Study      | Average daily study hours                           |
| Sleep_Hours      | Average daily sleep hours                           |
| Internships      | Number of internships completed                     |
| Projects         | Number of academic/personal projects completed      |
| CGPA             | Cumulative GPA (0–10 scale)                         |
| Placement_Score  | Composite score (0–100) from placement tests & interviews |
| Placed           | 1 = Placed, 0 = Not placed                          |

---

## Project Structure

- **Task2_Improved_Notebook.ipynb** – Main notebook with data preprocessing, modeling, evaluation, and insights.
- **student_career_performance.csv** – Dataset used for training and evaluation.
- **README.md** – Project documentation.

---

## Steps Performed

### Part A – Data Preprocessing
- Removed duplicate rows based on Student_ID.
- Replaced missing values with median.
- Removed data logical error

### Part B – Logistic Regression
- Built a classification model to predict placement (Placed column).
- Evaluated with Accuracy, Precision, Recall, F1-Score, and ROC AUC using.
- Visualized results with a Confusion Matrix and ROC Curve.

### Part C – Linear Regression
- Built a regression model to predict Placement_Score.
- Evaluated using Mean Absolute Error (MAE), Mean Squared error (MSE), Root Mean Squared Error (RMSE).
- Created a Predicted vs. Actual plot to visualize performance.


### Part D – Comparison & Insights
- Compared the performance and use cases of Linear vs. Logistic Regression.
- Provided data-driven insights on student performance and placement readiness.

---

## Key Insights

1. **Study Hours are a Strong Predictor**  
   Students who dedicate more hours to study per day are significantly more likely to be placed.

2. **CGPA is a Key Factor**  
   Students with CGPA above 7.0 have a substantially higher probability of being placed, while those below approximately 6.5 are at risk.

3. **Practical Experience Improves Outcomes**  
   Completing at least two internships and three projects significantly increases placement readiness and likelihood of selection.

---

## Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---



# Dependencies
- pip install pandas numpy scikit-learn matplotlib seaborn
