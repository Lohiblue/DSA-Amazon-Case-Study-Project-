# DSA-Amazon-Case-Study-Project-

This repository contains sample Excel project, templates, pivot table and Excel dashboard i have created after my Beginner's Data Analysis class with DSA.

##  PROJECT TOPIC: Amazon Case Study

### PROJECT OVERVIEW: 
This Data Analysis project aims to analyze product and customer review data to generate insights that can guide product improvement, marketing strategies, and customer engagement. 

### DATA SOURCE:
 The primary Data used for this analysis is an Excel  Amazon product Review Analysis and this Data was gotten from Incubator Hubs
 
### TOOLS USED
The tools used for this Analysis are:
 - Ms. Excel for Data cleaning
 - Ms. Excel Pivot table and pivot chat for visualization and excel dashboard
   

### DATA CLEANING AND PRESENTATION
In the initial phase of this process, the Excel Data was loaded and inspected, observable features like unnecessary long names were trimmed using functions that deals with text. Some columns in the data set were also hidden to make the data more presentable. The Category column was also subdivided into other columns using the text to column command. Some new 
columns were created based on the analysis and then formatting of the data set.


### EXPOSITORY DATA ANALYSIS
This involves the exploring of the Data to answer some questions such as:
  - What is the average discount percentage by product category?
  - How many products are listed under each category?
  - What is the total number of reviews per category?
  - Which products have the highest average ratings?
  - What is the average actual price vs the discounted price by category?


### DATA ANALYSIS
The data set was analyzed using some excel functions and pivot tables and chart. During the process of the analysis, excel functions such as Average, IF, COUNT, MAX, SUM etc. were used to determine some based conditions. Some of the Excel formulas used to create new columns and calculated columns includes
  - =IF(Discount % >= 50, "Yes", "No") Then use a COUNTIF
  - =IF(Discounted Price < 200, "<₹200",  IF(Discounted Price <= 500, "₹200–₹500", ">₹500")):
  - =IF([@Discount%]<=10, "0-10%",  IF([@Discount%]<=20, "11-20%",  IF([@Discount%]<=30, "21-30%", ...)))
  - =(Actual Price - Discounted Price) / Actual Price * 100 




