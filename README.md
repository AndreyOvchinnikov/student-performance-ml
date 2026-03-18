# 🎓 Student Performance Analysis & Prediction

## 📌 Project Goal

The goal of this project is to analyze factors affecting student performance and build a machine learning model to predict student grades.

---

## 📊 Dataset

The dataset contains information about students, including:

* hours_studied
* attendance_percent
* homework_done
* age
* city
* club

---

## 🔍 Exploratory Data Analysis (EDA)

* Checked data structure and completeness
* Identified key features influencing grades
* Analyzed relationships between variables

---

## 🧠 Hypotheses

1. Students who study more hours have higher grades
2. Students who complete homework have higher grades

---

## 📈 Data Insights

* Strong positive relationship between `hours_studied` and `grade`
* Positive relationship between `attendance_percent` and `grade`
* Students who complete homework perform significantly better
* No clear relationship between `age` and `grade`

---

## 🤖 Model

* Model: Linear Regression
* Features used:

  * hours_studied
  * attendance_percent
  * homework_done

---

## 📉 Evaluation

Metric: Mean Absolute Error (MAE)

* Model with 2 features → MAE ≈ 0.259
* Model with 3 features → MAE ≈ 0.247

✅ Adding `homework_done` improved model performance

---

## 📌 Conclusion

* Study time and homework completion are key factors
* Attendance also contributes to performance
* Irrelevant features (like age) can reduce model quality

---

## 🚀 Technologies

* Python
* pandas
* scikit-learn
* matplotlib
