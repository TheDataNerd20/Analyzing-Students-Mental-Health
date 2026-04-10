# Analyzing-Students-Mental-Health

📊 International Students Mental Health Analysis (SQL Project)
This project analyzes how the length of stay affects the mental health of international students using SQL. It explores trends in depression, social connectedness, and acculturative stress to understand how students adapt over time.

📌 Project Overview
This project analyzes how the length of stay in a foreign country affects the mental health of international students, using a real dataset from a Japanese university study (2018).
The goal is to uncover whether students adapt over time by examining trends in:
Depression levels (PHQ-9)
Social connectedness (SCS)
Acculturative stress (ASISS)

🎯 Business Problem
International students often face challenges such as:
Cultural adjustment
Social isolation
Academic pressure
This project answers:
❓ Does staying longer in a host country improve mental health outcomes?

🛠️ Tech Stack
PostgreSQL
SQL (Aggregation, Filtering, Grouping)
Data Analysis Concepts

📂 Dataset Details
Column	Description
inter_dom	International or Domestic student
stay	Length of stay (years)
todep	Depression score (PHQ-9)
tosc	Social connectedness score
toas	Acculturative stress score

🔍 SQL Approach
Filtered international students only
Grouped data by stay
Calculated:
Total students per group
Average mental health scores
Rounded values to 2 decimal places
Sorted results by stay (descending)
