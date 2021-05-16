# Project Name here
- author(s): 
      Wilson Hinh, [ Wilson.hinh@baruchmail.cuny.edu ]
		  Lei Zhang, [ lei.zhang2@baruchmail.cuny.edu ]
		  David Pun, [ David.Pun@baruchmail.cuny.edu ]
		  Macrin Francis, [ macrin.francis@baruchmail.cuny.edu ]
- date created: 5/12/2020
- class: CIS 9440

Project Objective: Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications

Project Tools:
The tools used to build this Data Warehouse were: (change this to make applicable to your project)
1. For data integration - python
2. For data warehousing - Google BigQuery
3. For Business Intelligence - Tableau

## Kimball Lifecycle Project Stages

### Project Planning

Motivation for project:
Provide insight for investors to gauge the market and make well informed investment decisions, with relevant trends and continuous changes that occur over time. 

Description of the issues or opportunities the project will address:
Aim to increase the number of transactions of property being bought/sold with forecasting price changes based on income, down payment, credit score, locations, size, from a buyer’s and seller’s perspective. 

Project Business or Organization Value:
$1,000,000

Data Sources:
1. NYC Open data 
2. Sales Dataset: https://www1.nyc.gov/site/finance/taxes/property-rolling-sales-data.page
3. COVID Dataset: https://github.com/nychealth/coronavirus-data
4. Rent Dataset: https://streeteasy.com/blog/data-dashboard/?agg=Total&metric=Inventory&type=Sales&bedrooms=Any%20Bedrooms&property=Any%20Property%20Type&minDate=2010-01-01&maxDate=2021-03-01&area=Flatiron,Brooklyn%20Heights

### Business Requirements Definition

List of Data Warehouse KPI's:
1. Total Covid Cases per Borough from 2020-2021
2. Relationship between Covid cases and death
3.Average Sale Price vs Covid Case per Borough
4. Average Rent Price and Covid Cases
5. Ownership Transfer from parents to children during Covid

### Dimensional Model

This project's Dimensional Model consists of 4 Facts and 2 Dimensions

![Dimensional Model](/Volumes/LZ/Baruch College/2021_CIS9440 data warehousing/9440/dimFact table-2.png)

This project's Kimball Bus Matrix:

![Kimball Bus Matrix](/Volumes/LZ/Baruch College/2021_CIS9440 data warehousing/9440/kimball bus metrix.png)

### Business Intelligence Design and Development

List of Visualizations for each KPI:
1. Bar Chart for comparison of ...
2.
3.
...

BI Application Wireframe design:

Use correct file path here to show picture of Wireframe design...
![Alt text](/img/wireframe_design.JPG)

Picture of final Dashboard:

Use correct file path here to show picture of Dashboard...
![Alt text](/img/Dashboard.JPG)

### Deployment

The project was deployed on Tableau Public: (link here)
