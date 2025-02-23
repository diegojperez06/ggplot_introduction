# Hotel-Booking_R

## Table of Content

- [Project Overview](#project-overview)
- [Datasources](#datasources)
- [Tools](#tools)
- [Querying desired data in SQL](#querying-desired-data-in-sql)
- [Excel Process](#excel-process)
- [Tableau Dashbaord](#tableau-dashbaord)
- [Conclusion](#conclusion)

### Project Overview
---
In this project I work for a hotel booking company and I am tasked with presenting different visualizations to answer a variaty of business questions. To do this, I imported the companies data to RStudios and installed the ggplot2 package to visualize the data. Finally I exported the visualization into a R Markdown notebook to easily share with shareholders.

### Datasource
---

Hotel_bookings.csv: Primary datasource used for this project was downloaded from the internet and loaded into RStudios. 

### Tools
---

For this activity I used R in RStudios. R offers flexible and straightforward codes through packages for professional data visuals. 

### Code
---

#Importing csv file and saving as a data frame called 'hotel_bookings'

hotel_bookings <- read.csv("hotel_bookings.csv")

   

### Excel Process
---

1. Over four thousand rows were loaded, the easiest way to clean up the data was by pivoting the query.

   - Mismatching customer address were updated
   - Misspelled words were corrected
   - Incorrect quantities inputted in databse were corrected.
  
2. Once data was cleaned up and ready for use began creating inital dashbaord in Excel. This allows me to have a vision in mind for what the final product should look like.
   
3. Created graphs by pivoting different the data in different ways to get all the aspects I wanted in the final dashbaord.

4. Once all the graphs were created, a slcier connection was used to filter all the graphs by year, state or store.
  
### Tableau Dashbaord
---

1. Imported the Query from Excel to Tableau.
   
2. Built 7 different workbooks to slice up where the revenue was coming from.
   
   	-  Revenue Per Year
   	-  Revenue Per Month
   	-  Revenue Per State
   	-  Revenue By Store
   	-  Revenue By Category
   	-  Top Customers
   	-  Revenue by Sales Rep
  
3. Created 3 "banner" worksheet to display a general overview of the companies performance over the years using serveral key meterics as a guage.
  
 4. Finally dahsboard was created with the ability to filter by year and state to give managment the flexability to display the data however they desired.


### Conclusion 
---

This project consited of working through the data analysis process to answer the business need. I was asked to provide a snapshot of the companies financials over the span of three years. Using the data analysis proces of

1. Understanding the problem (no visbaility into revenue drivers)

2. Collect and gather data (qurying desire data from companies databse)

3. Clean the data
   
4. Gather and analyze/visualize the data
   
5. Interpret the resutls (create interacgive dashboard to management to make more accurate decisons going forward)

I helped managment make more infomrmed decisons mnoving forward. 
