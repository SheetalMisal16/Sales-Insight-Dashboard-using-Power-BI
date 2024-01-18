# Sales-Insight-Dashboard-using-Power-BI
Problem statement

AtliQ Hardware, a prominent company specializing in the distribution of computer hardware and peripherals across various branches in India, is currently grappling with significant challenges in comprehending the overall business performance. The Sales Director is encountering difficulties in gauging the reasons behind the underwhelming sales figures, which have been on a steady decline. When reaching out to regional managers for updates on sales and market conditions, the Sales Director faces resistance as these managers find it inconvenient and frustrating to derive insights from numerical data presented in Excel files.

The company's sales team is struggling to convey crucial information effectively, hindering the decision-making process. To address this issue, a more user-friendly and accessible method of presenting data may be required to facilitate a smoother flow of information between the sales team and management.

Solution

Sales director of the AltiQ hardware, decided to build a PowerBI Dashboard for converting the data into visual representation to make data driven decisions. So, he hired a team of data people to complete this task.

AIMS Grid
By using the AIMS grid project management tool, we made sure what are the purpose, stakeholder, end result and success criteria of our project.


![AIMS grid sales insights](https://github.com/SheetalMisal16/Sales-Insight-Dashboard-using-Power-BI/assets/126179390/f233f05c-2088-48f4-a9a8-5e79b9d90f3d)

Steps Followed in this project

Learned about AIMS grid for project planning.
Used MySQL for retrieving the data from the database into Power BI.
Data Cleaning in power query.
Performed ETL process (Extract Transform and Load)
Created measure for needs and used them for creating visuals in PowerBi.
In the currency there were two types of currencies in transactions, performed currency conversion to make all the currency type same
Data Validation
Data Modelling and Visualization.

Major Changes/ Customizations Made

1.Solved the ‘(blank)’ problem for the products section by deleting the original products table and adding the self-modified products table (where I have added the Products ranging from Prod280 to Prod339 with their product type (random type- b/w ‘Own Brand’ and ‘Distribution’). 2.Merged the original modified ‘sales_transaction’ table with the new ‘sales_transaction’ table having profit margin, cost price, etc.

Insights

In this dashboard, we can see company has generated total revenue in 4 years ₹ 985M, total profit margin ₹24.7M, Profit margin% 2.5%, Sales Qty ₹2M. in 2020 company has generated total revenue of ₹ 142M by selling a total of 350K and earned a profit of ₹ 2.1M.
In 4 years Delhi NCR is our largest market in terms of revenue with ₹ 520M and total contribution of 52.8% with total revenue but if you look at the profit margin Delhi NCR is generating only 2.3% profit margin.
If we check the profit margin then here In 2020 Bhubaneshwar comes into the picture which is generating the highest profit margin of 10.48%. Similarly, if we can check the Profit Contribution % by Market then here Mumbai is the largest player with 23.89% of total contribution in total profit.
In 4 years Bengaluru generating the lowest profit margin of -20.8%.if we can check the Profit Contribution % by Market then here also Bengaluru is the Lower with -0.3% of total contribution in total profit.
In our top 5 customers, the Electricalsara Stores is our biggest customer who has generated total ₹ 413 M revenue generated in 4 years.
In our top 5 products,the Prod318 is our highest product has generated total ₹ 69M revenue generated in 4 years.
In product type Distribution has generated the revenue of ₹494M and ownbrand revenue is ₹494M generated in entire 4 years.
Revenue Trend is showing that in June 2020 revenue has been decreased drastically compared to the revenue last year and the profit margin was the least in April 2020.
Key Learnings

Learned about what real business data sets look like.
Learned about how to write some major analysis queries in MySQL.
how to connect the database’s tables to Power Bi and how to clean & modify the unwanted data in Power Query.
Learned about some major practical DAX functions and measures.
Learned about some major analytical visuals and reports.

Final result

Dashboard KPI Page

![sales1](https://github.com/SheetalMisal16/Sales-Insight-Dashboard-using-Power-BI/assets/126179390/dee98c25-ed37-4be0-a63f-1c97ccc9ec1f)

Dashboard Performance Insights

![sales2](https://github.com/SheetalMisal16/Sales-Insight-Dashboard-using-Power-BI/assets/126179390/10fc1b00-42d3-4fd0-a87c-387540697331)

Dashboard Profit Analysis


![sales3](https://github.com/SheetalMisal16/Sales-Insight-Dashboard-using-Power-BI/assets/126179390/e261897b-73fa-4099-a754-2278295df6f9)
