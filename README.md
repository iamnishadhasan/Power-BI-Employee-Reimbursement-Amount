# Power-BI-Employee-Reimbursement-Amount
This is a solution on an Power BI exercise of Data Analytics Bootcamp. I am uploading it to record my Data Analytics Journey.

## What are the insights I needed to find
- The expense type column has some spelling and punctuation errors, correct them
- Project names are not uniform, make it uniform.
- The Currency column has some missing values, based on the amount, create a new custom column.
- Condition: amount >= 1000, = INR; amount < 1000, = USD; else = EURO
- Convert the "amount" column to INR based on the "currency" column. Use the USD and Euro to INR exchange rates. Assume blank and INR values remain unchanged.
- Create a measure to calculate the sum of reimbursed amount in INR.
- Use the calculate function and check the total reimbursed amount for Project_B
- Create a measure to check the count of declined requests.
- Create a slicer visual for the Project and employee
- Create a column chart for employees and reimbursement amount.
- Create a pie chart for Project vs reimbursement amount
## KPI's in the Report
- Sum of Total Reimbursed Amount in INR.
- Total Reimbursed Amount in INR only in Project_B.
- Total number of "Declined" Payment Requests.
- Include two filters based on Project Name and Employee Name.
- Creating Column Chart of Total Reimbursed Amount in INR based on Employee Name.
- Creating Pie Chart of Total Reimbursed Amount in INR by Project Name.
