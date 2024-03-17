# New York Property Sale Analysis

## Table of Content

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitation](#limitation)
  



### Project Overview

This  Sales Analysis is aimed at providing insight on the propery market of New York between the third Quarter of 2016 and the third quarter of 2017

[nyc-rolling-sales (version 1).xlsx](https://github.com/Bamscrown/New-York-Property-Sales-Analysis/files/14628187/nyc-rolling-sales.version.1.xlsx)



![Screenshot 2024-03-17 105858](https://github.com/Bamscrown/New-York-Property-Sales-Analysis/assets/163521119/cbb9b76c-26db-4143-9f21-a82037f76587)


### Data Source

The Primary Data Set used for this Analysis is an "Excel file.xlsx" obtained from "Kaggle" with information about the property sale in the New York between the third Quarter of 2016 and the third Quarter of 2017. The data contains infromation such as the Boroughs in the New York, the unit sold, the property type  i.e wether the property sold is a commercial property or a residential property, the property selling price, sales date, Property Cathegory at the time of purchase and present, the property tax category at the time of purchase and present , amongst others
   [Download here](https://www.kaggle.com/datasets/new-york-city/nyc-property-sales)

                                    
### Tools

- Excel Power Query - Data Cleaning [Download here](https://microsoft.com)
- Excel Pivot Table - Data Analysis
- Excel Pivot Chat -Dashboard


 ### Data Cleaning
 
In the data cleaning /prepartion the following were carried out

- Data  inspection to have proper understanding of the data set
- Checks amd removal of duplicates using Remove duplicate function
- Address Column Was combined with the block number column using the Flash fill function and labelled "Address"
- Empty cells in Sale price columns were replaced with $0 values using find and replace function
- Blank rows were also removed using the filter /delete function
  

### Exploratory Data Analysis

EDA involved exploring the data to answer key questions, such as

- What is the total sales price per borough
- What is the total Units sold per borough
- What  is the total Units of each property type sold per borough
- Does the tax Category of a property at the time of sale influence the decison to sell the property
- What is the total units of property acquired by inheritance
  

 ### Data Analysis
Several relationshp tables were created to answer the EDA questions listed above.
The following relationship tables were created

- Table 1 : Total Property units sold in each borough to know which borough has the highest and the least sales and what factor could be responsible
- Table 2 : Total Sales price of properties in each borough to gain insight into the borough that has the highest sales price and what effect each property values have on the result
- Table 3 : Property Units sold per each quarter
- Total Unit sold per Tax Category as a time of sales to determine the effect tax policies have on property sale
- Total Units sold per property type in each borough


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


### Limitation

The properties that were acquired by inheritace had a sales price value of $0. All empty cells in sales price column were replaced with $0 value but this may not be the reality as some of the empty cells may be omitted and not necesaary that the property was sold for $0(inherited)



  

