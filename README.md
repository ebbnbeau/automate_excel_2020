# automate_excel_2020

First project that I got a glimpse of python's true power. 
## Cut this monthly task duration by 90%, and preserved my sanity.

Background:
I had a monthly sales transaction file (excel) that I pull from our SAP database for the entire company (on average 200k rows 40 columns). I was responsible to clean, transform, distribute, and calculate commissions for 45+ sales reps.

Files: 
1. Monthly sales transaction file
2. Sales Rep File
  a. Summary sheet
  b. Sales by customer sheet
  c. Current month sheet
  d. Temporary pivot table sheet that group by customer id get sum of sales ($)

Task roadmap: 
1. Slice sales data on individual reps on the monthly file (file 1)
2. Create new worksheet (file 2c) within each rep file (file 2) for current month that's being worked on
3. Paste sliced data (task 1) into worksheet (2c)
4. Format the worksheet (2c)
5. Create a worksheet (2d) with pivot table summary of the data within (2c)
6. Insert label cells and calculation cells (2c) (might've removed this step for efficiency)
7. Left join (2b) on customer id to (2d)
8. Save (2)

I had other cells/sheets that contained excel formulas that would do the calculation.
