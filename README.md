# 📊 International Students Mental Health Analysis

## 📌 Overview
This project analyzes how the **length of stay** affects the **mental health of international students** using a real-world dataset from a Japanese university study conducted in 2018. The analysis focuses on identifying trends in depression, social connectedness, and acculturative stress as students spend more time in a foreign country.

---

## 🎯 Objective
The main objective of this project is to determine whether longer stays in a host country help international students:
- Reduce depression levels (PHQ-9)
- Improve social connectedness (SCS)
- Decrease acculturative stress (ASISS)

---

## 🛠️ Tech Stack
- **PostgreSQL**
- **SQL (Aggregation, Filtering, Grouping)**
- Data Analysis Techniques

---

## 📂 Dataset Description

| Column Name | Description |
|------------|-------------|
| inter_dom  | Student type (International or Domestic) |
| stay       | Length of stay (in years) |
| todep      | Depression score (PHQ-9 test) |
| tosc       | Social connectedness score (SCS test) |
| toas       | Acculturative stress score (ASISS test) |

---

## 🔍 Methodology
- Filtered the dataset to include only **international students**
- Grouped data based on **length of stay (`stay`)**
- Calculated:
  - Number of students per group (`count_int`)
  - Average depression score (`average_phq`)
  - Average social connectedness score (`average_scs`)
  - Average acculturative stress score (`average_as`)
- Rounded all average values to **two decimal places**
- Sorted the results by **length of stay in descending order**

---
