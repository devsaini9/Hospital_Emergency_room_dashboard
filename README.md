# Patient Dashboard Analysis

This project provides a comprehensive analysis of patient data using **Power Query** and **Power Pivot** in Excel to transform and visualize important insights. The data is analyzed to generate key performance indicators (KPIs) and visualizations that will help healthcare professionals make informed decisions about the hospital's emergency room performance and patient satisfaction.

## Objective

The main objective of this project is to analyze and visualize the following key metrics from the hospital's patient data:

1. **Daily number of patients in the emergency room.**
2. **Average patient satisfaction score.**
3. **Average patient wait time.**
4. **Breakdown of patients by age group.**
5. **Patient count by department referral.**
6. **Patient attendance status (On-time vs Delayed).**
7. **Gender-wise analysis of patients (Male vs Female).**
8. **Patient admission status (Admitted vs Not Admitted).**

By analyzing these metrics, the goal is to gain insights into patient behavior, hospital performance, and identify areas for improvement.

## Techniques Used

1. **Power Query**: 
   - Used to load, transform, and extract data from the provided source.
   - Applied data cleaning, formatting, and filtering operations to ensure accurate data analysis.

2. **Power Pivot**: 
   - Built relationships between multiple tables to create a robust data model.
   - Added calculated columns to generate the necessary KPIs.
   - Created measures to calculate average wait time, satisfaction score, and more.

3. **Pivot Tables & Charts**: 
   - Designed pivot tables to aggregate data and derive insights.
   - Created separate pivot tables and charts for each key metric.

4. **Slicers**: 
   - Added interactive slicers to allow users to filter the data by month and year.

5. **Pie Charts**:
   - Created pie charts to visualize patient attendance status and gender distribution.

## KPIs and Findings

### 1. Daily Number of Patients in the Emergency Room
   - **KPI**: Total number of patients admitted to the emergency room each day.
   - **Finding**: The daily count shows patient volume trends, helping identify peak hours and days.

### 2. Average Patient Satisfaction Score
   - **KPI**: Average satisfaction score of patients admitted.
   - **Finding**: This score helps assess overall patient experience, providing insights into areas of improvement.

### 3. Average Waiting Time
   - **KPI**: The average wait time patients experience before receiving care.
   - **Finding**: A longer wait time could indicate inefficiencies in hospital operations or a higher volume of patients during certain periods.

### 4. Number of Patients by Age Group
   - **KPI**: The number of patients categorized by different age groups.
   - **Finding**: Identifying age demographics can help tailor care services to the most frequent patient age groups.

### 5. Number of Patients by Department Referral
   - **KPI**: The count of patients referred by different departments.
   - **Finding**: Understanding the department breakdown helps manage resource allocation and identify trends in department referrals.

### 6. Patient Attendance Status (On-time vs Delayed)
   - **KPI**: Percentage of patients that attended their scheduled appointment on time versus those that were delayed.
   - **Finding**: Delays in patient attendance can help identify operational bottlenecks or areas needing attention in scheduling.

### 7. Gender-wise Analysis of Patients
   - **KPI**: The ratio of male vs. female patients.
   - **Finding**: Provides insights into patient gender distribution, which may affect resource planning and services offered.

### 8. Admission Status (Admitted vs Not Admitted)
   - **KPI**: The count of patients who were admitted versus those not admitted.
   - **Finding**: Provides insight into how many patients are admitted and may reveal opportunities to improve bed availability or admission procedures.

## Visualizations

### 1. **Graphs on Separate Sheets**
   - **Graph 1**: Daily number of patients in the emergency room.
   - **Graph 2**: Average satisfaction score of patients.
   - **Graph 3**: Average waiting time for patients.

### 2. **Age Group Breakdown**
   - A bar chart showing the number of patients by different age groups.

### 3. **Department Referral Breakdown**
   - A bar chart showing the number of patients referred by each department.

### 4. **Attendance Status Pie Chart**
   - A pie chart showing the proportion of patients who attended on time versus those who were delayed.

### 5. **Gender-wise Patient Distribution**
   - A pie chart showing the number of male vs. female patients.

### 6. **Slicers**
   - **Month-wise Slicer**: Filter data based on the month of admission.
   - **Year-wise Slicer**: Filter data based on the year of admission.

### 7. **Admission Status Table**
   - A table displaying the count of patients who were admitted versus those who were not admitted.

## Suggested Solutions Based on Findings

1. **Improve Patient Satisfaction**: 
   - Identify areas contributing to low satisfaction scores (e.g., waiting times, staff behavior) and implement improvement initiatives.
   
2. **Optimize Wait Time**:
   - Address high wait times by analyzing peak admission periods and ensuring adequate staffing and resources during those times.
   
3. **Resource Allocation**:
   - Reallocate resources based on department referrals and the age groups most frequently admitted to ensure efficiency.

4. **Attendance Management**:
   - Implement strategies to reduce patient delays, such as automated reminders, better scheduling, and improved patient communication.

5. **Gender-Specific Services**:
   - Assess whether there are gender-based differences in care requirements and adjust services accordingly to cater to both male and female patients equally.

6. **Admission Process Optimization**:
   - Review admission procedures to reduce the number of patients who are not admitted, potentially improving bed management and reducing overcrowding.
