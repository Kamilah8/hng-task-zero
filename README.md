# First Glance Technical Report

## Introduction

This report provides an initial analytical insights of a Sale dataset consisting of 2824 rows and 25 columns related to Customer order, Product and Sales details.

**Project Purpose**
The purpose of this project is to explore the dataset and gain initial insights from the data, identifying potential areas that needs further analysis.

**Dataset Information**
This dataset contains a Sales sample from 2003–2005 of Customers located in 19 countries, which includes; “Australia”, “Austria”, “Belgium”, “Canada”, “Denmark”,
“Finland”, “France”, ”Germany”, “Italy”, “Japan”, “Norway”, “Philippine”, ”Singapore”, “Spain”, Sweden”, “Switzerland”, “UK”, “USA”.
The dataset also comprises of 25 columns, which includes attributes such as;
* ORDER_NUMBER
* QUANTITY_ORDERED
* PRICE_EACH
* ORDER_LINE_NUMBER
* SALES
* ORDER_DATE
* STATUS
* QTR_ID
* MONTH_ID
* YEAR_ID
* PRODUCT_LINE
* PRODUCT_CODE
* CUSTOMER_NAME
* PHONE
* ADDRESS_LINE1
* ADDRESS_LINE2
* CITY
* STATE
* POSTAL_CODE
* COUNTRY
* TERRITORY
* CONTACT_LAST_NAME
* DEAL_SIZE
  
There are also numeric columns which includes; QUANTITY_ORDERED, PRICE_EACH, SALES, ORDER_LINE_NUMBER, MSRP

### Data Source
sales_data_sample: The dataset used for this analysis is the ["sales_data_sample.csv"](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data),containing detailed 
information about sale made by a company.

### Tool
* Excel


### OBSERVATION

**The Year with the Highest Sales**

The year 2004 had the highest number of Sales with a significant amount of 4,724,162.60 followed by 2003 with a significant amount of 3,516,979.54 then 2005, which seems to have the lowest Sales.


Sales distribution by the Year
**Country with the highest Sales**

The analysis of Sales within Countries shows that Customers from USA had the highest number of Sales, followed by Spain, then France. This shows the potential countries for marketing.


Sales distribution by Country
**Sales and Product_line sold Per Year**

The year 2004 had an increase in Sales for Classic Cars with a significant amount of 1,762,257.09. With Cars Sales having a progressive increase among the years. This shows that most Customers go for Classic cars rather than others from the Product_line


Product_line vs Sales
Number of Product_line Ordered.

This analysis showed the Quantity_order of Product_line ordered each year along with it prices. And 2004 had the highest Quantity_order as compared to others.


Product_line,Year vs Sum of Quantity_Ordered, Sum Price
### CONCLUSION

The analysis from the Sales dataset focused on Countries with the highest purchase of the Product_line(i.e highest number of Sales), Product_line with the highest Sales and the year with the most Sale. It also highlighted the potential countries to focus on ( USA, Spain, France). This analysis also indicated the Product_line(Classic Cars) as the most sold item. From 2003–2005, there was a steady increase in Sales, peaking at 2004, declining in 2005. The data revealed an over roll increase in Sales from Classic Cars.

### SUGGESTION

The suggestions include; getting Customers feedback for canceled order and other feedbacks as well, Understanding customer demands/needs.





