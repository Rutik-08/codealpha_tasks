# HR Analytics Dashboard (using Power BI)

&#x20;This repository contains an **HR Analytics Dashboard** developed using Microsoft Power BI, providing interactive visualizations of key workforce data. The dashboard integrates employee demographics, performance metrics, satisfaction scores, and other HR variables to reveal trends and insights.  By applying analytics to HR data, organizations can improve performance – for example, industry sources note that people analytics can increase productivity by \~25% and cut attrition by \~50%.

## Screenshots

&#x20;![HR Analytics Dashboard Screenshot](https://raw.githubusercontent.com/Rutik-08/codealpha_tasks/main/Screenshot%202025-07-10%20193354.png)
The screenshot above shows our HR Analytics Dashboard interface in Power BI. It visualizes workforce metrics (such as total employees, new hires, and separations) using charts and cards. Similar to Microsoft’s HR sample dashboard, it highlights trends in hiring and turnover, helping HR managers spot issues and opportunities at a glance.

## Dataset

&#x20;Our project uses an HR dataset containing typical people-analytics variables: employee details (age, gender, department, etc.), performance ratings, satisfaction and engagement survey scores, and related fields. These variables are commonly analyzed in HR analytics to drive business decisions. Together, the data enables comprehensive analysis of workforce trends, performance, and employee feedback across the organization.

## Project Structure

The repository is organized as follows (all files are in the `main` branch):

* **Readme file:** [README.md](https://github.com/Rutik-08/codealpha_tasks/blob/main/README.md) – This overview file (you are here) that explains the project.
* **Raw dataset files:** Key data files used by the dashboard:

  * [Employee\_data.csv](https://github.com/Rutik-08/codealpha_tasks/blob/main/Employee_data.csv) – Employee demographics and status details.
  * [Retrenched\_employees.csv](https://github.com/Rutik-08/codealpha_tasks/blob/main/Retrenched_employees.csv) – List of employees who have been retrenched.
  * [HR\_Analytics\_Data.csv](https://github.com/Rutik-08/codealpha_tasks/blob/main/HR_Analytics_Data.csv) – Consolidated HR metrics used for analysis.
  * [Due\_for\_promotion\&retrenchment.xlsx.xlsx](https://github.com/Rutik-08/codealpha_tasks/blob/main/Due_for_promotion%26retrenchment.xlsx.xlsx) – A spreadsheet identifying employees due for promotion or retrenchment.
* **HR\_analytics\_dashboard.pbix:** [HR\_analytics\_dashboard.pbix](https://github.com/Rutik-08/codealpha_tasks/blob/main/HR_analytics_dashboard.pbix) – The Power BI file containing the dashboard. This `.pbix` file holds all the interactive visualizations built on the datasets. *Feel free to open this file in Power BI Desktop to view or modify the visuals.*

## Dashboard Components

The HR Analytics dashboard consists of several report pages and visuals, including:

* **Overview:** A high-level summary of key HR metrics. It displays total number of employees, attrition/turnover rates, counts of employees due for promotion or exit, and other KPI cards. This page gives a snapshot of the workforce and business health.
* **Employee Distribution:** Charts and graphs showing how employees are distributed across branches, departments, job roles, age groups, and education levels. These visuals help identify patterns or imbalances (e.g. department size or age-group breakdown). Distribution analysis like this is a standard HR analytics practice, helping to see where staff are concentrated or sparse.
* **Due Promotion Analysis:** Details on employees flagged for promotion or retrenchment. This component uses fields like “Promotion status” and “Retrenchment status” to highlight who is due for promotion or scheduled for exit. It provides insights into upcoming HR actions (e.g. succession planning and severance planning).
* **Employee Feedback Analysis:** Insights from survey and performance data. It examines metrics such as employee satisfaction, work-life balance, and performance ratings. By visualizing feedback data, this component uncovers patterns in engagement and morale. As HR analytics guides improvement, analyzing such survey results helps pinpoint issues and drive retention strategies.

Each of these dashboard pages uses interactive charts (bar/column charts, pie charts, slicers, etc.) to allow drilling into the data and filtering by categories. Together, they enable HR teams to explore the organization’s data in a cohesive, visual manner.

**Sources:** Project and dataset details are based on the repository content.  Relevant industry insights and definitions are cited from HR analytics references.
