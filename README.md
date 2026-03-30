# -python-assignment-part4:
# Student Performance Analysis & Prediction (Part 4)

This project analyzes student performance data, creates visualizations, and builds a machine learning model to predict whether a student will pass or fail.

---

## 🔹 Features Implemented

### 1. Data Exploration (Pandas)
- Loaded dataset using pandas
- Displayed first 5 rows, shape, and data types
- Generated summary statistics
- Counted pass vs fail students
- Compared average subject scores for pass and fail groups
- Identified the top-performing student based on average score

---

### 2. Data Visualization (Matplotlib)
- Bar chart: Average score per subject
- Histogram: Distribution of math scores with mean line
- Scatter plot: Study hours vs average score (Pass vs Fail)
- Box plot: Attendance comparison (Pass vs Fail)
- Line plot: Student-wise comparison of math and science scores

---

### 3. Data Visualization (Seaborn)
- Bar plots comparing math and science scores (Pass vs Fail)
- Scatter plot with regression line for attendance vs performance
- Observed that Seaborn provides better styling and simpler syntax compared to Matplotlib

---

### 4. Machine Learning (Scikit-learn)
- Built a Logistic Regression model
- Features used:
  - math, science, english, history, pe
  - attendance_pct, study_hours_per_day
- Performed:
  - Train-test split (80-20)
  - Feature scaling using StandardScaler
- Evaluated:
  - Training accuracy
  - Test accuracy
- Displayed predictions vs actual results
- Analyzed feature importance using model coefficients
- Predicted result for a new student

---

## 🔹 Files Included

- `part4_visualization_ml.ipynb` – Main notebook with all tasks
- `students.csv` – Dataset used for analysis
- `README.md` – Project documentation

---

## 🔹 Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔹 How to Run

1. Open the notebook in Google Colab or Jupyter Notebook
2. Upload `students.csv`
3. Run all cells:
4. Ensure all outputs and plots are visible

---

## 🔹 Notes

- The dataset is small, so model accuracy may vary
- The goal is to demonstrate the complete workflow:
- Data analysis → Visualization → Machine Learning
