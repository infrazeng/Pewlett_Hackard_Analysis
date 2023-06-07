# Pewlett Hackard Analysis

## Tools Used
• SQL

• PGAdmin

• QuickDBD

## Purpose and Overview

Pewlett Hackard recognizes the importance of proactive workforce planning and aims to anticipate upcoming vacancies. To gain insights into the number of employees expected to retire in the next year and identify the individuals involved, we conducted a thorough analysis using SQL, QuickDBD, and PGAdmin.

Our analysis involved identifying employees who were approaching retirement age and organizing them into a comprehensive list categorized by department and job title. By employing SQL, we efficiently extracted the necessary data to determine the potential impact on each department within the company.

This approach enables Pewlett Hackard to proactively assess which departments will experience the most significant changes due to impending retirements. Armed with this knowledge, the company can effectively prepare strategies and implement appropriate measures to mitigate any potential workforce gaps that may arise.

By leveraging the power of data analysis and utilizing tools such as SQL, QuickDBD, and PGAdmin, Pewlett Hackard is equipped with valuable insights to facilitate strategic planning, ensuring a smooth transition during this upcoming period of change.

## Results

### Deliverable 1: 
• The first list of retiring employees shows more than 133,000 results. However, many of the names are repeated since the employees may have held many positions

![](/Resources/retirement_titles.png)
• When we apply the SELECT DISTINCT ON function with the employee number, we find that the list of retiring employees shrinks down to about 90,000

![](/Resources/unique_titles.png)
• From there, we filtered the data to find out which titles were going to see the most amount of employees retiring. These were the results:

![](/Resources/retiring_titles.png)

### Deliverable 2:
• Many of the retiring employees may be eligible for the company's mentorship program. To find the employees eligible, we filtered the data for retiring employees born in the year 1965
![](Resources/eligibility.png)

## Summary

Based on the comprehensive data obtained from the unique_titles table, it has been determined that Pewlett Hackard will need to address a substantial workforce turnover, with over 90,000 positions requiring replacement due to impending retirements. Significantly, a considerable number of these retirees hold senior positions within the company.

To ensure a smooth transition and maintain operational continuity, it becomes imperative for Pewlett Hackard to initiate a robust training program aimed at equipping a large number of younger employees to assume these vital roles before the retirees' departure. This analysis underscores the critical importance for organizations to not only anticipate potential labor-related challenges but also to proactively address other crucial aspects within their business ecosystem.
