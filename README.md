
**Empployee Attrition Analysis Dashboard**
This repository contains the source files and documentation for an interactive Employee Attrition Dashboard built using Tableau. 
The dashboard provides a comprehensive overview of employee turnover within the organization, aiming to identify key drivers and patterns to support data-driven HR strategies.


📌 Project Overview
Employee attrition is a critical metric for any organization as it impacts business continuity, productivity, and costs.
This project visualizes a fictional HR dataset to uncover insights into why employees are leaving.
The dashboard consolidates key attrition metrics and breakdowns by various demographic and organizational factors, 
making it an effective tool for HR professionals, managers, and leadership.

🎯 Key Insights & Analysis
The dashboard highlights several critical areas of concern and interest:

Overall Attrition Rate: The company is experiencing an attrition rate of 16.12%, with 237 employees leaving out of a total of 1,470.

Departmental Disparity: The Sales Department is the most significant contributor to attrition,
accounting for 56.12% of all employee departures. This suggests a potential issue with the work environment, compensation, or management within this department.

Gender Dynamics: While the total workforce numbers are not shown by gender, males account for a higher absolute number of attritions (150) compared to females (87).

Age-Related Trends: Attrition is most prevalent among the 25-34 age group, with 112 employees from this bracket leaving. 
This indicates that the company may be struggling to retain early to mid-career professionals.

Impact of Education Field: Employees with a background in Life Sciences (89 attritions) and Medical (63 attritions) are leaving at the highest rates.
This could point to a misalignment between their career expectations and the opportunities available within the company.

Job Satisfaction: The Job Satisfaction Rating table provides a detailed view across different job roles. While not directly correlated with attrition in this view,
it serves as a crucial metric for deeper analysis. For instance, Sales Executives and Laboratory Technicians have a wide distribution of satisfaction scores, which could be investigated further.

🛠️ Technical Details
Visualization Tool: Tableau Desktop

Data Source: Anonymized HR employee dataset 

Dashboard Components:

KPI Cards: High-level metrics for quick insights (Total Employees, Attrition Count, Attrition Rate, Active Employees, Avg. Age).

Interactive Filters: The dashboard can be filtered by Education.

Charts Used: Pie Chart, Bar Chart, Heatmap/Table, and custom visuals for demographic breakdowns.

📂 Repository Contents

README.md: This documentation file.

img/ folder: Contains the dashboard screenshot.


💡 Potential Future Improvements
Correlation Analysis: Directly link Job Satisfaction scores to Attrition Rate to establish a clear correlation.

Predictive Modeling: Integrate a predictive model to identify employees who are at high risk of leaving.

Time-Series Analysis: Add a view to track attrition trends over months or years.

Deeper Dive: Analyze attrition based on other factors like Years at Company, Salary, and Performance Rating.
