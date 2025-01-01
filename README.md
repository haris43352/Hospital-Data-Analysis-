**Hospital Data Analysis Dashboard **

**Overview**

This project focuses on analyzing hospital data to understand key metrics, identify patterns, and provide actionable insights for improving patient outcomes and doctor performance. The analysis covers aspects such as treatment types, triage levels, patient outcomes, and feedback.

The process includes data cleaning, exploratory data analysis (EDA), and visualization to create a clear picture of operational trends. The insights are visualized using Tableau to aid decision-making.

**Steps Performed in Analysis**

1. Exploratory Data Analysis (EDA)
Removed null values to ensure data quality and accuracy.
Corrected data types where necessary (e.g., converting categorical fields to appropriate formats).
Performed initial exploration to identify patterns in the data, such as relationships between treatment types and triage levels, or doctor performance and patient outcomes.
Identified areas requiring further investigation, such as high deceased rates for specific doctors and low satisfaction scores.

**3. Visualization**

Created multiple visualizations to interpret and communicate the data effectively:
Triage Levels by Doctor: Analyzed the distribution of triage levels managed by each doctor.
Treatment Types by Doctor: Compared the number of surgeries, consultations, and medications by each doctor.
Doctor Performance by Outcomes: Evaluated deceased and recovery rates for each doctor.
Satisfaction Scores and Feedback: Mapped patient satisfaction against feedback to identify service gaps.
Peak Hour Analysis: Determined patient inflow trends during peak hours to optimize resource allocation.

**Key Insights and Observations**

1.** Triage Levels vs. Doctor**

Dr. ID 102 handled the highest number of high triage level patients, while Dr. ID 104 dealt with the majority of low triage cases.
Action Point: Balance the distribution of high triage level patients to avoid overburdening specific doctors.
2. **Treatment Type vs. Doctor**

Dr. ID 104 performed the most surgeries (14), followed by Dr. IDs 103 and 105 (11 each).
Dr. ID 102 provided the highest number of consultations and medications.
Action Point: Investigate Dr. ID 104's ability to manage surgeries efficiently and replicate these methods across other doctors.
3. **Doctor ID vs. Patient Outcomes**

Dr. ID 101 had the lowest deceased rate (2), indicating better patient management.
Dr. ID 102 had the highest deceased rate (13), despite being highly active in consultations and medications.
Action Point: Analyze Dr. ID 102's treatment approach and patient demographics to identify improvement opportunities.

4.** Doctor ID vs. Satisfaction Score**
Dr. ID 105 had the highest average satisfaction score (5.0).
Surprisingly, Dr. ID 101, with the lowest deceased rate, received a low satisfaction score (2.0), which may be linked to long waiting times for patients.
Action Point: Address patient wait times for Dr. ID 101 and understand factors driving high satisfaction for Dr. ID 105.

**5. Doctor ID vs. Feedback**

Dr. ID 104 received the highest count of positive feedback ("good service"), correlating with efficient handling of patients and a moderate deceased rate.
Action Point: Use Dr. ID 104’s methods as a benchmark for other doctors.

**6. Peak Hour Analysis**
Patient counts peak during specific hours, creating high demand during those times.
Action Point: Adjust staffing schedules and resources to handle peak-hour patient inflow effectively.

**Additional Observations**
The combination of low satisfaction scores for Dr. ID 101 and long wait times suggests a need to improve patient flow management.
Dr. ID 102’s high activity in medications and consultations, combined with high deceased rates, requires an in-depth review of treatment protocols and patient handling practices.
The high satisfaction scores for Dr. ID 105 could be due to effective communication and better time management during treatments.
**
Recommendations**

Optimize Workload Distribution: Ensure a more even distribution of high triage level patients and surgeries among doctors to improve efficiency and outcomes.
Enhance Training: Focus on areas like time management and effective patient communication, particularly for Dr. ID 101.
Improve Peak Hour Operations: Allocate more resources and staff during peak hours to handle the increased patient load efficiently.
Analyze Treatment Approaches: Review Dr. ID 102’s practices to reduce the deceased count while maintaining patient satisfaction.
Leverage Positive Practices: Replicate the successful methods of Dr. ID 104 and Dr. ID 105 to boost overall performance and satisfaction.

**Tools and Technologies Used**

Python: For EDA and data preprocessing using Jupyter Notebook.
Tableau: For visualizing insights through interactive dashboards.
Pandas & Matplotlib/Seaborn: To clean, analyze, and visualize data during EDA.
