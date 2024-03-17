# New York Property Sale Analysis

## Table of Content

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)rtr of @0
- [Recommendations](#recommendations)
  

  
### Project Overview

This  Sales Analysis is aimed at providing insight on how the propery market of New York between the third Quarter of 2016 and the third quarter of 2017

[nyc-rolling-sales (version 1).xlsx](https://github.com/Bamscrown/New-York-Property-Sales-Analysis/files/14628187/nyc-rolling-sales.version.1.xlsx)



![Screenshot 2024-03-17 105858](https://github.com/Bamscrown/New-York-Property-Sales-Analysis/assets/163521119/cbb9b76c-26db-4143-9f21-a82037f76587)


### Data Source

The Primary Data Set used for this Analysis is a "Excel file.xlsx" cotaining detail information about the property sale in the New York between the third Quarter of 2016 and the third Quarter of 2017. The date contains infromation such as the Boroughs in the New York, the unit sold, the proeprty type sold i.e wether the property sold is a commercial property or a residential property, the sale sprice, sales date, Property Cathegory, the property tax category, the tax category amongst others
   -[Download here](https://www.kaggle.com/datasets/new-york-city/nyc-property-sales)

### Tools

- Excel Power Query - Data Cleaning [Download here](https://microsoft.com)
- Excel Pivot Table - Data Analysis
- Excel Pivot Chat -Dashboard

 ### Data Cleaning
 
In the data cleaning /prepartion the following were carried out

- Data  inspection
- Checks amd removal of duplicates
- Changing of M, F and S  syntax in Gender and Marital Status Columns to Male, Female and Single for proper understanding and definition
- Using "IFS"  function to create a new coloumn to specifiy the age range as Old, Middle Age and Adolescent using the age data in the Age column
  
### Exploratory Data Analysis

EDA involved exploring the data to answer key questions, such as

- Compare the age bracket to the count of bike purchase
- Compare the purchase of bike with the average income of the customers
- Which Gender Purchases more Bikes
- How do the Education of the customer affect the bike purchase
- the Effect of individual Commute distance on the bike purchase

 ### Data Analysis
Several relationshp tables were created to answer the EDA questions listed above.
Three major realtionship tables were created

- Table 1 : Count of bike Purchase of bike base on the customer gender
- Table 2 : Avearge income of the customer base on their gender to determine the gender and the average income of the customer that either bought or did not buy a bike
- Table 3 : Count of bike purchase base on the customer cummute distance

- ### Results
  
  The Analysis Results are summarised as follows;
  - The demand for bike is higher within the Adolescent age bracket as such the age is a significant factor on the purchase of bike
  - The higher the income of rhe customer the more interested in purchasing a bike
  - Commute distance of the customer does not affect the purchase of a bike
  - The purchase of a bike is not significantly impacted by the Gender of the customer

### Recommendations

Base on the result of the  Analysis, i recommend the following actions,
- The marketing strategy of the organisation should focus more on the Middle age bracket between 30 and 54 years old,  they are more interested in purchasing a bike
- The Marketing strategy should also focus more on the higher income earners within the entire region
- The marketing starategy should not also be gender focused as both the male and female are interested in purchasing a bike espcially when the earn more 



  
