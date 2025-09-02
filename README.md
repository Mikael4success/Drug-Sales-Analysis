# Drug Sales Analysis

### Introduction
---
Using **Power BI Desktop**, I transformed, modeled, and visualized the data to uncover trends, identify top and underperforming products/customers, and highlight key revenue drivers.
The report consists of three pages:
1. Top/Bottom Analysis
2. Customer Analysis
3. Trend Analysis

### Problem Statement
---
-	Monitor overall sales performance and profitability
-	Identify top-performing and underperforming drugs/customers
-	Understand customer demographics and buying patterns
-	Track sales trends over time for strategic planning

### Skills Demonstrated
---
-	Power BI Desktop
-	DAX for calculated measures
-	Power Query (M) for data transformation
-	Excel / CSV for source data
-	PowerPoint for designing dashboard template

### Data Sourcing
---
The data was downloaded in CSV file, and extracted it into Power BI for cleaning, analysis, and visualization.
It contains 3 sheets/tables:
1. DrugLookup with 41 rows and 6 columns
2. Customer with 201 rows and 7 columns
3. Fact(Order) with 16315 rows and 6 columns

### Data Transformation
---
Data was efficiently cleaned and transformed with the Power Query Editor of Power BI. Some of the applied steps include:
- Promoted first rows as headers in the Fact, Customer and Drug Table.
- Merged columns of first and last names to get the full name of each customer in the Customer Table
- Removed column, othercustomerinfo, as it was not necessary for the analysis in the Customer table.
- Added conditional column, Age Group, in the Customer table.
- Removed column, Treat, as it was not necessary for the analysis in the Drug table.
- Datatype change to TEXT.

### Data Modelling
---
![](SS_model.png)

I manually connected relatable tables resulting in a star schema model and they are as follows: 
- The DrugID in the DrugLookup Table connected to the DrugID in the FactTable
- The CustomerID in the Customer table connected to the CustomerID in the FactTable 
- The Date in the Calendar table connected to the SalesDate in the FactTable

### PowerPoint Templates
PPt Top/Bottom    |    PPt Customer    |    PPt Trend    |    PPt Tooltip
:-----------------:|:------------------:|:--------------:|:--------------:
![](PPt_dashboard_top.jpg)|![](PPt_dashboard_customer.jpg)|![](PPt_dashboard_trend.jpg)|![](PPt_tooltip.jpg)

This were the customized layouts used for each of the reports created in PowerPoint.

### Analysis and Visualization

#### Top/Bottom Dashboard

![](SS_Top(1).png)

![](SS_Top(2).png)
