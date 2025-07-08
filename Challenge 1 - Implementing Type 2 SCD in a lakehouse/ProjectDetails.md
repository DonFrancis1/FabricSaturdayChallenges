# Project Details

💡 Microsoft Fabric Challenge: Implement SCD Type 2 in Lakehouse
🎯 Objective
Use PySpark in a Microsoft Fabric Lakehouse to implement Slowly Changing Dimension Type 2 (SCD Type 2) to track changes in employee records over time.

🗂️ Scenario
Your company maintains an employee_master table with records such as name, department, and job title. Over time, employees may change departments or job titles. You need to track historical changes using SCD Type 2 logic in the dim_employee dimension table.


✅ Success Criteria
SCD Type 2 implemented correctly using PySpark.

No duplicate active records.

Correct handling of unchanged vs. changed rows.

🧪 Bonus
Add unit tests or validation checks:

Count of current vs. historical records

Row count consistency over time

📁 Deliverables
Participants must submit:

Notebook: SCD Type 2 Implementation

Screenshot of final dim_employee table

Explanation of SCD Type 2 logic in comments or markdown cells
