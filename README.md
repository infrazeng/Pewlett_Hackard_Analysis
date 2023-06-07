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

From the data gathered from the unique_titles table, a little over 90,000 positions will need to be filled as employees retire. Many of those retiring are in senior positions and so they will need to train large amounts of younger employees to fill their roles before they retire. This analysis demonstrates the need for companies to predict not only potential problems with labor, but with other sectors of their business as well.
