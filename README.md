

Imagine a bustling city where the skyline is dotted with towering buildings, vibrant markets, and a diverse population. However, beneath this bustling exterior lies a pressing issue: the widening gap between the cost of living and average salaries. This scenario is not unique to one city but is echoed across many regions globally.

I am excited to share my latest Mentorness Project  focused on analyzing the cost of living across various cities and countries. In an era where financial stability and quality of life are paramount, understanding the intricate dynamics between income and expenses is more critical than ever.

🔍 Project Overview:
This project delves into comprehensive data analysis to uncover the major cost components contributing to the overall cost of living. By examining key factors such as housing, transportation, and average salaries, I aim to provide actionable insights that can guide individuals, organizations, and policymakers in making informed decisions.

💡 Key Insights/Business Questions

The cost of living is a crucial metric that impacts individuals and businesses alike. Understanding the cost
of living in different cities and countries is vital for making informed decisions regarding relocation,
investment, or business expansion. This project aims to address several key questions:

• What are the cities and countries with the highest and lowest costs of living?
• What are the major cost components contributing to the overall cost of living in a region?
• How do factors like average salary, housing costs, and transportation expenses correlate with the
cost of living?
• Are there any trends or patterns in the data that can help individuals and organizations make
strategic decisions?

About The Dataset

The dataset utilized in this project is sourced from Numbeo, a collaborative online database that
provides cost of living information worldwide. It contains 56 columns, including information about cities,
countries, and a wide array of cost-related variables, ranging from grocery prices to real estate costs. The
dataset is designed to offer a comprehensive view of the economic aspects of various locations, making
it a valuable resource for conducting cost of living analyses.

Variable Description:

The dataset consists of the following variables:
• City: Name of the city.
• Country: Name of the country.
• ColumnDescription
• city Name of the city
• countryName of the country
• x1 Meal, Inexpensive Restaurant (USD)
• x2 Meal for 2 People, Mid-range Restaurant, Three-course (USD)
• x3 McMeal at McDonalds (or Equivalent Combo Meal) (USD)
• x4 Domestic Beer (0.5 liter draught, in restaurants) (USD)
• x5 Imported Beer (0.33 liter bottle, in restaurants) (USD)
.............................................................
.............................................................
• x54 Average Monthly Net Salary (After Tax) (USD)
• x55 Mortgage Interest Rate in Percentages (%), Yearly, for 20 Years Fixed-Rate

• data_quality 0 if Numbeo considers that more contributors are needed to increase data
quality, else 1data_quality: A binary variable (0 or 1) indicating data quality, with 0 suggesting
the need for more contributors and 1 indicating satisfactory data quality.

Data preprocessing and Cleaning

I noticed that the column names were represented with numbers instead of their actual, descriptive values
I researched the Numbeo website to find and make the necessary corrections, grouped the cost factors into categories using custom column in Power Query as
market, Groceries, utilities, childcare, transportation, Housing etc.


Changed Datatypes 

The value 0 in the "data quality" column indicates that the data quality for the respective row is considered "poor", "fail", or does not meet the predefined quality criteria. It suggests that the data in this row might be incomplete, inconsistent, or inaccurate, and may require further cleaning, verification, or exclusion from certain analyses.

I filtered the rows in excel, In PowerBI hid the data quality column to reduce columns and enhance data performance.

Removed few rows with No values.
calculated the “average cost of living” column using the custom column in Power Query
Created a Dax measure "Salary to Cost of Living Gap."

Insights for Strategic Decisions

For Individuals:
Relocation Decisions: Professionals, especially remote workers, can consider relocating to cities with a lower cost of living to maximize their disposable income and savings.
Career Choices: Pursuing careers in high-demand fields within lower-cost regions can offer a strategic advantage in terms of financial stability.
For Organizations:
Salary Adjustments: Companies operating in high-cost cities should consider adjusting their salary structures to align with living expenses, ensuring employee satisfaction and retention.
Remote Work Policies: Encouraging remote work can help employees manage their living costs better and improve overall productivity and morale.
Investment in Benefits: Providing housing stipends, transportation allowances, and other benefits can help bridge the cost-of-living gap for employees.

For Policymakers:
Affordable Housing Programs: Implementing and expanding affordable housing initiatives can make a significant impact on reducing the cost-of-living burden.
Public Transportation Development: Investing in efficient and affordable public transportation systems can help lower the overall living expenses for residents.
Economic Diversification: Encouraging a diverse economic environment can create more balanced job opportunities, reducing the dependence on high-income sectors alone.

In Conclusion
The data reveals clear trends and patterns that highlight the disparity between cost of living and salaries across various regions. By understanding these trends, individuals can make informed decisions about their careers and living arrangements, organizations can better support their employees, and policymakers can implement targeted measures to create more balanced and equitable living conditions. Through strategic actions informed by data, we can work towards bridging the gap and enhancing the quality of life for all.











