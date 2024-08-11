# group-1_project-1
**Project Proposal: Comprehensive Analysis of Health Trends**

**1. Introduction**  
Understanding health trends is essential for identifying emerging health issues, shaping public health policies, and enhancing healthcare services. This project aims to analyze key health trends by examining prevalent medical conditions, demographic influences, and insurance providers. The objective is to uncover patterns and correlations that can provide actionable insights for stakeholders.
Our team, consisting of Brianna, Derek, Kavita, and Laquita, has conducted an in-depth analysis using the healthcare dataset from the "Unlocking Healthcare Trends: Data Analysis" project authored by Muhammad Furqan. The dataset, sourced from Kaggle, contains 10,000 synthetic patient records, which include a wide range of attributes such as patient demographics, medical conditions, and admission details. The data is entirely synthetic and is intended for educational and non-commercial use.
The analysis was conducted using Python, along with libraries such as Pandas and Matplotlib, to perform data cleaning, analysis, and visualizations. These tools enabled us to explore the relationships among various variables in the dataset and draw meaningful conclusions.

**2. Objectives**  
The objectives of this project are as follows:
Analyze Gender-Based Susceptibility to Medical Conditions:
Identify the prevalence of medical conditions among male and female populations within the dataset.
Determine which gender is more susceptible to specific medical conditions.
Evaluate Billing Amounts for One-Day Hospital Stays:
Use statistical analysis to determine the highest billing amounts for various medical conditions during a one-day hospital stay.
Examine Insurance Provider Coverage:
Identify the most prevalent medical conditions covered by different insurance providers.
Compare the average billing amounts associated with each medical condition by insurance provider.
Analyze Hospital Admission Types by Age Group:
Compare the frequency of different hospital admission types (Elective, Emergency, Urgent) across various age groups.
Determine the Most Commonly Admitted Conditions:
Identify the medical condition with the highest admission rates and the corresponding insurance provider with the highest admission frequency.

**3. Data Sources**  
Primary Dataset: Kaggle Health Dataset (health_dataset.csv)

**4. Methodology**  
Data Collection:
Extract relevant data from the dataset, focusing on health conditions, billing information, insurance providers, duration of hospital stays, and admission types.
Data Cleaning and Preparation:
Clean and wrangle the data to address missing values, outliers, and inconsistencies.
Merge datasets as needed to create a comprehensive dataset for analysis.
Exploratory Data Analysis (EDA):
Conduct EDA to understand data distribution and identify patterns or trends.
Generate summary statistics for each variable to provide a foundational understanding of the dataset.
Visualization:
Create various visualizations, such as bar charts, heatmaps, pie charts, and bell curves, to illustrate the trends and correlations in the data.
Utilize these visualizations to present findings in a clear and comprehensible manner.
Interpretation and Recommendations:
Interpret the results of the analysis to draw conclusions about the health trends identified.
Provide recommendations based on these findings to inform healthcare policies and practices.

**5. Expected Outcomes**  
***Insurance Provider and Medical Condition Correlation:***
Conclusion: Arthritis and Asthma are most commonly associated with Cigna, Cancer and Hypertension with United Healthcare, Diabetes with Medicare, and Obesity with Blue Cross.
***Admission Types by Generation:***
Conclusion: Generation X has the highest rates of Elective and Urgent admission types, while Seniors exhibit the highest rates of Emergency admissions.
***Billing Amounts for One-Day Hospital Stays:***
Conclusion: Hypertension incurs the highest average billing cost for a one-day hospital stay, with significant variance in billing amounts as depicted by a bell curve. One-day hospital stay for managing hypertension had the highest billing cost in this data-set.
The higher probability density peak and wider spread in standard deviation plot suggested more variability in terms of individual billing amounts. Also, indicative of potential outliers, (high/low billing amounts) contributing to the variability
***Gender-Based Prevalence of Medical Conditions:***
Conclusion: The prevalence of medical conditions amongst the females was slightly more for arthritis & obesity. Males were slightly more prone for asthma, cancer & hypertension. Both Males & females were equally prone for diabetes.
***Trends in Admissions Over Time:***
Conclusion: There was a steady increase in admissions into 2020, followed by a decline to regular admission numbers later. Additionally, older age is correlated with a higher prevalence of health conditions.  

***This cohesive analysis aims to provide a comprehensive understanding of the health trends reflected in the dataset, offering valuable insights for healthcare providers, policymakers, and other stakeholders. The findings and recommendations derived from this study have the potential to guide targeted interventions and improve overall healthcare outcomes.***
