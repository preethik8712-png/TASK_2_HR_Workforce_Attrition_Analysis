📊 HR WORKFORCE ATTRITION ANALYSIS

📌 Project Overview

Employee attrition is one of the key challenges faced by organizations today. High attrition rates can lead to increased recruitment costs, loss of experienced employees, reduced productivity, and overall organizational instability.

This project focuses on analyzing employee attrition using HR data and uncovering meaningful patterns through data visualization. The project is implemented entirely using Power BI, where data cleaning, transformation, and dashboard creation are performed to generate actionable insights.

🎯 Objectives

* To analyze employee attrition patterns
* To identify key factors influencing employee turnover
* To build an interactive HR analytics dashboard
* To derive meaningful insights for decision-making
* To suggest strategies for improving employee retention


🛠️ Tools & Technologies Used

* **Power BI** – Dashboard creation and visualization
* **Power Query** – Data cleaning and transformation
* **DAX (Data Analysis Expressions)** – KPI calculations
* **Microsoft Excel / CSV** – Dataset handling



📂 Project Structure

TASK_18_HR_Workforce_Attrition_Analysis
│
├── data
│   └── IBM_HR_Attrition.csv
│
├── dashboard
│   └── HR_Attrition_Dashboard.pbix
│
├── images
│   ├── dashboard_page1.png
│   ├── dashboard_page2.png
│
├── reports
│   └── HR_Attrition_Report.pdf
│
├── README.md
└── requirements.txt




📊 Dataset Description

The dataset contains comprehensive employee-related information, including:

👤 Demographic Features

* Age
* Gender
* Education
* Marital Status

💼 Job-related Features

* Department
* Job Role
* Business Travel
* Years at Company

💰 Financial Features

* Monthly Income
* Salary Band (Derived)

😊 Behavioral Features

* Job Satisfaction
* Work-Life Balance
* OverTime

🎯 Target Variable

* Attrition (Yes / No)

🔄 Data Preparation (Power BI)

The following steps were performed using Power Query:

* Removed duplicate records
* Checked and handled missing values
* Converted data types for consistency
* Created calculated columns:

  * Salary Band (Low / Medium / High)
  * Experience Group (0–5, 6–10, 10+ years)
* Filtered irrelevant columns

📌 Key Performance Indicators (KPIs)

The dashboard includes the following KPIs:

* 👥 Total Employees
* 📉 Attrition Rate (%)
* 📈 Retention Rate (%)
* 💰 Average Monthly Income
* ⏳ Average Tenure
* 😊 Job Satisfaction Score
* ⏱️ Overtime Percentage

📈 Dashboard Features

The Power BI dashboard provides interactive and dynamic visualizations:

* Attrition by Department
* Attrition by Job Role
* Salary Band vs Attrition
* Overtime vs Attrition
* Job Satisfaction vs Attrition
* Age Group vs Attrition
* Experience vs Attrition

Users can filter and explore data using slicers for deeper analysis.

🔍 Detailed Analysis

1. Department-wise Attrition

Sales department shows a higher attrition rate compared to other departments, possibly due to workload and pressure.

2. Salary Analysis

Employees with lower salaries tend to leave more frequently, indicating compensation plays a major role.

3. Overtime Impact

Employees working overtime have significantly higher attrition rates due to poor work-life balance.

4. Job Satisfaction

Low job satisfaction is directly linked to higher employee turnover.

5. Experience Analysis

Employees in the early stage of their careers (0–5 years) are more likely to leave.

💡 Key Insights

* High attrition observed in Sales department
* Overtime is a major factor contributing to attrition
* Low salary employees are at higher risk
* Job satisfaction strongly impacts retention
* Early-career employees are more likely to leave

 📉 Business Impact

* Increased hiring and training costs
* Reduced employee productivity
* Loss of experienced workforce
* Negative impact on organizational growth

✅ Recommendations

 🔹 Improve Work-Life Balance

* Reduce excessive overtime
* Introduce flexible working hours

 🔹 Enhance Compensation

* Revise salary structures
* Provide incentives and bonuses

🔹 Employee Engagement

* Conduct feedback sessions
* Recognize and reward performance

 🔹 Career Development

* Provide training programs
* Offer promotion opportunities

 🚀 Future Scope

* Build machine learning models to predict attrition
* Implement real-time HR dashboards
* Perform advanced analytics and forecasting
* Integrate employee feedback analysis

📌 Conclusion

This project demonstrates how data visualization and analytics can help organizations understand employee attrition. By identifying key influencing factors such as salary, overtime, job satisfaction, and experience, organizations can take proactive steps to reduce attrition and improve workforce stability.

 🙌 Acknowledgement

Dataset: IBM HR Attrition Dataset


