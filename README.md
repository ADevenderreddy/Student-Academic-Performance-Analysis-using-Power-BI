# 🎓 Student Academic Performance Analysis using Power BI

## 📊 Project Overview

This project focuses on analyzing student academic performance data collected from two Portuguese schools. The dataset — `student-mat.csv` — was sourced from the **UCI Machine Learning Repository** and contains information on students’ grades, demographic, social, and school-related features.
The main objective of this project is to identify key factors that influence student achievement and visualize them using **Microsoft Power BI**.

---

## 🧠 Objectives

* To understand how demographic, social, and academic factors affect student performance.
* To analyze patterns related to **absences**, **study time**, **parental education**, and **alcohol consumption**.
* To design a **Power BI Dashboard** providing actionable insights for educators and policymakers.
* To classify students based on their performance levels for better academic intervention.

---

## 🧾 Dataset Information

**File:** `student-mat.csv`
**Source:** UCI Machine Learning Repository
**Attributes:**

* **Demographic:** Age, Gender, Address, Family Size, Parental Education, Parental Job
* **Academic:** Study Time, Failures, School Support, Paid Classes, Higher Education Interest
* **Behavioral:** Absences, Free Time, Going Out, Daily Alcohol, Weekend Alcohol
* **Performance:** G1, G2, G3 (Grades across terms)

---

## 🧩 Data Analysis & Transformation

1. Imported and cleaned the dataset in **Power BI**.
2. Created calculated columns:

   * `FinalGrade` (Average of G1, G2, G3)
   * `PerformanceCategory` = *High / Medium / Low* based on `FinalGrade`
   * `AbsenceCategory` = *High Absence / Low Absence* using an IF condition
3. Managed missing values and data types for smooth visualization.
4. Used DAX for data categorization and measure creation.

---

## 📈 Power BI Dashboard Insights

The interactive Power BI dashboard provides insights such as:

* **Average Grades by Gender**
* **Impact of Study Time on Final Grades**
* **Relationship Between Absences and Academic Performance**
* **Effect of Parental Education and Job on Student Success**
* **Correlation between Alcohol Consumption and Grades**
* **Distribution of Students by Performance Categories**

---

## 💡 Key Findings

* Students with **longer study times** tend to achieve **higher grades**.
* **Higher parental education levels** correlate with better academic outcomes.
* **High absences** significantly reduce student performance.
* Moderate **weekend alcohol consumption** negatively impacts grades.
* Male and female students show **comparable performance**, with minor variations in behavioral attributes.

---

## 🛠️ Tools and Technologies

* **Power BI** – Data visualization and dashboard design
* **Microsoft Excel / CSV** – Dataset handling
* **DAX (Data Analysis Expressions)** – For calculated fields and measures
* **UCI Repository** – Data source

---

## 📂 Project Files

| File Name         | Description                                                     |
| ----------------- | --------------------------------------------------------------- |
| `student-mat.csv` | Dataset containing student academic and demographic information |
| `student.pbix`    | Power BI dashboard file visualizing the insights                |
| `README.md`       | Project documentation file                                      |

