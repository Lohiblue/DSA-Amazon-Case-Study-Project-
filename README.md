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

    ![Excel ](https://github.com/user-attachments/assets/e5128956-aec9-4306-b34b-4d084d7a8292)
    
    ![excel 2](https://github.com/user-attachments/assets/fb22d366-a54a-4d2a-83d6-b6a3d91ef676)
    
    ![excel 5](https://github.com/user-attachments/assets/6f309877-891e-4dad-a4a1-046bc26cdce4)
    
    ![excel 4](https://github.com/user-attachments/assets/1811bb8c-7e39-4865-826e-6036b12ed024)
    
    ![excel 3](https://github.com/user-attachments/assets/a86b8829-093e-4dba-9473-8f1f159acf44)

    
### Result findings
Conclusively, after the analysis some of the following findings were made
  - The average discount percentage by each category was 48%
  - The product listed under each category was a total of one thousand four hundred and sixty five (1465)
  - The total Number of reviews per category was  26,766,377
  - The products with the highest Average rating of 5% each
     - Syncwire LTG to USB Cable for Fast Cha
     - REDTECH USB-C to Lightning Cable 3.3FT
     - Amazon Basics Wireless Mouse | 2.4 GHz
  - The average actual price vs the discounted price  by category were Average 5357 and 3125 etc








