# Codealpha_task1


**TASK 3: Data Visualization – Student Performance Dataset**

This repository showcases a comprehensive data visualization project using the Student Performance dataset. It was created as part of an internship task to uncover patterns in student scores and present data-driven insights in a clear, visual, and actionable format.

---

**TASK Objectives**

* Transform raw data into visual formats like charts, graphs, and dashboards
* Use tools like Matplotlib and Seaborn for creating visuals
* Design visuals that enhance understanding and reveal insights clearly
* Craft a compelling data story to support educational decision-making
* Build a strong portfolio with impactful and well-designed visualizations

---

**Key Questions Explored**

1. How does gender affect student performance?
2. What impact does test preparation have on scores?
3. Does parental education level influence student outcomes?
4. Is there a relationship between lunch type and performance?
5. Are math, reading, and writing scores correlated?

---

**Data Summary**

* File: data/student_data.csv
* Columns:

  * Categorical: gender, race/ethnicity, parental level of education, lunch, test preparation course
  * Numerical: math score, reading score, writing score
* Cleaning:

  * No missing values
  * No outliers detected
  * No encoding required for visual analysis

---

**Visualizations Created**

* Bar Plot – Average scores by gender
* Bar Plot – Test prep vs performance
* Box Plot – Parental education vs scores
* Violin Plot – Lunch type vs scores
* Heatmap – Score correlation

---

**Data Story: Unlocking What Impacts Student Success**

**Objective:**
Use visual analysis to uncover key performance drivers in student academic data and guide improvements in teaching, testing, and parental engagement.

**Insight 1: Gender-Based Subject Strengths**

* Females scored higher in reading and writing
* Males slightly outperformed in math
* Action: Use gender-sensitive teaching — encourage boys in reading, support girls in math confidence

**Insight 2: Test Preparation Makes a Difference**

* Students who completed the prep course scored 10–15 points higher on average
* Action: Make test prep programs widely available or mandatory

**Insight 3: Parental Education = Student Performance**

* Higher the parental education level, higher the student scores
* Action: Run parental involvement workshops for those with lower education levels

**Insight 4: Lunch Type Highlights Inequality**

* Students with standard lunch outperformed those with free/reduced lunch
* Action: Provide academic support and mentorship for students from low-income families

**Insight 5: Strong Score Correlations**

* Math, Reading, and Writing are positively correlated
* Action: Strengthen literacy programs to improve overall academic performance

---

**Summary of Decisions You Can Support**

* Target gender-specific learning gaps
* Expand access to test preparation programs
* Support low-income and low-education families
* Improve curriculum to leverage subject interdependence

---

**Project Structure**

StudentPerformance\_DataViz/
├── data/
│   └── student\_data.csv
├── images/
│   ├── avg\_scores\_gender.png
│   ├── avg\_scores\_test\_prep.png
│   ├── scores\_by\_parent\_education.png
│   ├── scores\_by\_lunch\_type.png
│   └── score\_correlation\_heatmap.png
├── notebooks/
│   └── StudentPerformance\_Visualization.ipynb
├── README.md
└── requirements.txt

---

**Tools Used**

* Python
* Pandas – Data handling
* Seaborn – Statistical plots
* Matplotlib – Custom visual styling

---

**How to Run**

1. Clone the repository(https://github.com/chandana-gc06/Data-Visualization)
2. Install the requirements using:
   pip install -r requirements.txt
3. Open the notebook in Jupyter:
   notebooks/StudentPerformance_Visualization.ipynb

---

