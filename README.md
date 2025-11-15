# Salary Data – Exploratory Data Analysis (EDA)

## Overview
This project explores a comprehensive salary dataset containing information on employee compensation across various roles, locations, and companies.  
The analysis focuses on understanding salary patterns, job title distributions, and regional differences in pay, while identifying trends within both technical and managerial career paths.

---

## Dataset Structure
The dataset includes 19 columns capturing details about workers, employers, and compensation:

- **Identification:** index, salary_id  
- **Employer Details:** employer_name  
- **Geographic Information:** location_name, location_state, location_country, location_latitude, location_longitude  
- **Job Information:** job_title, job_title_category, job_title_rank  
- **Experience:** total_experience_years, employer_experience_years  
- **Compensation:** annual_base_pay, signing_bonus, annual_bonus, stock_value_bonus  
- **Additional Information:** comments, submitted_at  

These variables allow for detailed analysis of how pay varies by country, state, job category, job title, and experience level.

---

## Analysis Summary
The exploratory data analysis was performed using Python and covered several key areas:

### 1. Variable Classification  
The dataset was examined by separating categorical features from numerical ones to better understand the structure of the data and prepare it for deeper analysis.

### 2. Role-Based Insights  
Specific job titles and job title categories were isolated to evaluate how compensation differs between technical roles such as software development, data-related roles, engineering management, and executive positions.

### 3. Geographic Salary Patterns  
The analysis compared salary levels across multiple states and countries, highlighting regions with the highest and lowest compensation for certain job categories.  
Particular focus was placed on identifying the most rewarding countries and states for data and software-related careers.

### 4. Salary Distribution and Ranges  
Various salary ranges were explored to understand how workers cluster within specific income brackets.  
This included filtering employees within defined earning thresholds and comparing pay across different job categories.

### 5. Mean and Aggregate Pay Evaluation  
Average salaries were computed for selected job titles and job title categories to identify:  
- the highest earners,  
- the lowest earners, and  
- roles with particularly strong compensation trends.

### 6. Comparative Job Category Analysis  
Technical job categories such as *Data* and *Software* were compared to determine which path offers a higher earning potential, especially within the United States.

### 7. Focused Multi-Role Examination  
A subset of notable tech roles was extracted to inspect their locations, employers, and job categories.  
Specific row selections were displayed to observe patterns within the data more clearly.

---

## Purpose of the Project
This analysis provides valuable insight into workforce compensation trends across the tech ecosystem.  
It serves as a useful reference for:

- job seekers evaluating competitive roles and locations,  
- employers assessing market positioning,  
- analysts studying salary distributions, and  
- learners practicing real-world data analysis techniques.

---

## Conclusion
By exploring job roles, salary brackets, geographic variations, and category-based comparisons, this project delivers a grounded understanding of how compensation differs across the technology industry.  
The results highlight where opportunities are strongest and which career paths show the most promising financial rewards.

