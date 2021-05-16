# NYC Real Estate Analysis During Pandemic

- Authors:
	* Wilson Hinh, Wilson.hinh@baruchmail.cuny.edu
 	* Lei Zhang, lei.zhang2@baruchmail.cuny.edu
 	* David Pun, David.Pun@baruchmail.cuny.edu
 	* Macrin Francis, macrin.francis@baruchmail.cuny.edu 

- Date created: 5/12/2020
- Class: CIS 9440 Data Warehousing

### Project Objective: 
Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications

### Project Tools:
The tools used to build this Data Warehouse were: 
1. For data integration - python
2. For data warehousing - Google BigQuery
3. For Business Intelligence - Tableau

## Kimball Lifecycle Project Stages

### Project Planning

1. Motivation for project:
Provide insight for investors to gauge the market and make well informed investment decisions, with relevant trends and continuous changes that occur over time. 

2. Description of the issues or opportunities the project will address:
Aim to increase the number of transactions of property being bought/sold/rent with forecasting price changes and pandemic changes

3. Project Business or Organization Value:
$1,000,000

Data Sources:
1. [Sales Dataset](https://www1.nyc.gov/site/finance/taxes/property-rolling-sales-data.page)
2. [COVID Dataset](https://github.com/nychealth/coronavirus-data)
3. [Rent Dataset](https://streeteasy.com/blog/data-dashboard/?agg=Total&metric=Inventory&type=Sales&bedrooms=Any%20Bedrooms&property=Any%20Property%20Type&minDate=2010-01-01&maxDate=2021-03-01&area=Flatiron,Brooklyn%20Heights)

### Business Requirements Definition

List of Data Warehouse KPI's:
1. Total Covid Cases per Borough from 2020-2021
2. Relationship between Covid cases and death
3. Average Sale Price vs Covid Case per Borough
4. Average Rent Price and Covid Cases
5. Ownership Transfer from parents to children during Covid

### Dimensional Model

This project's Dimensional Model consists of 4 Facts and 2 Dimensions
![Dimensional Model](https://github.com/leizhangg/NYC_Property_Sale_COVID/blob/main/image/dimFact%20table-2.png)

This project's Kimball Bus Matrix:

![Kimball Bus Matrix](https://github.com/leizhangg/NYC_Property_Sale_COVID/blob/main/image/kimball%20bus%20metrix.png)

### Business Intelligence Design and Development

List of Visualizations for each KPI:
1. Line Chart for comparison of Total Covid case per month  of each Borough in 2020 - 2021
2. Scatter Plot for comparison of Number of death out of COVID cases per day in 2020 - 2021 
3. Combination of Line chart and Bar chart for comparioson of Average Property Sales Price per Borough in 2020
4. Combination of Line chart and Bar chart for comparison of Average Property Rent Price per Borough in 2020
5. Treemap for comparison of Residential Ownership Transfer from parents to children of each month in 2020 -2021

BI Application Wireframe design:

![Alt text](https://github.com/leizhangg/NYC_Property_Sale_COVID/blob/main/image/Untitled%20Diagram.png)

Picture of final Dashboard:

![Alt text](https://github.com/leizhangg/NYC_Property_Sale_COVID/blob/main/image/Dashboard%201.png)

### Deployment

The project was deployed on Tableau Public: [Tableau Link](https://public.tableau.com/profile/lei.zhang3361#!/vizhome/m44/Dashboard1)
