# Business Insights 360
This is an end-to-end  Data Analysis and Power BI project which is based on an imaginary company called AtliQ Hardware.
## About AtliQ Hardware
AltiQ hardware is a company which has grown vastly in the recent years, and opened business all over the globe. It is a company which sells, computer and computer accessories through three mediums/channel

Retailers
Direct
Distributors Recently the company has faced a unforeseen loss by opening store in America based on the surveys, intuition and some excel analysis and also the company’s competitors has handful of analytics team to perform analysis and make data driven decision. So, the AltiQ hardware has no other option other than building their analytics team for data driven insights and decisions in the future to survive better in the industry.
Project kick off session, where you should get clear of for what and why this project and all other questions you have with regards to the project

## Problem Statement
AtliQ Hardware is struggling to do good business in Latin America.
So far all the decisions that AtliQ took have been based on some surveys and intuitions.

The company was doing some analysis using MS Excel files because of limited data. Now that the company has grown and has plenty of data to analyse, the management has decided to hire a Data Analyst. The management wants Data Analysts to utilise this data to make accurate and informed decisions.

Questions to ask before starting with dashboard
What is the objective of building this PowerBi dashboard?
In what terms the success of this project will be measured?
What will be time dead-line of the project?
do the stakeholders expecting pre-view before the actual release?
What are all the hopes stakeholders have out of this project?
what are all fears the stakeholder have in terms of building this dashboard?
Who are all will be using this dashboard and for what purpose?
what are all expectation the stakeholders have, by the completion of this project?
What can go wrong while building this project?
what are all the resources/ data needed to build this dashboard? is there any inputs from stakeholders in terms of design and views of the dashboard?
After the project kick off meetings, the data engineering team has given the data as per the request of data analytics team, let’s explore them.

 ## Management’s Dashboard Requirements
 The management wants to see these reports in the Power BI Dashboard:

### Finance View 
This will show the profit and loss statements across different products, markets, customers etc.

### Sales View 
To display the top-performing and bottom-performing customers with different key metrics.

### Marketing View 
Similar data as of Sales View but product based instead of customers.

### Supply Chain 
Reliability and accuracy to better understand the supply chain performance.

### Executive View  
This includes the integrated view of key insights for executives.

# Project Execution

## Step – 1
The first step was to load the data into MySQL Database and connect it to the Power BI.

## Step 2
Review and deleted the Database relationship created by Power BI by default.
Also, creating the required dimension table in Power Query.

## Step – 3
Data validation using some tables in Power BI and matching the values with the data provided.

## Step – 4
Data Transformation. For example, creating a Last Sales Month Reference table. So the last sales month reference table will be dynamic and will change after every sale.


## Step – 5
Created calculated columns in Power Query like fiscal_year and merged the tables.

## Step – 6
Data Modelling – Data modelling is a connection between different tables using a common table between them. In this project, Start Schema is used for Data Modelling where all the dimension tables were connected with Fact tables.

## Step – 7
Created calculated columns using more than 40 DAX formulas (Formulas listed at the bottom). After the columns were created, verified them in either MySQL or Excel file.

## Step – 8
This was the last step before start creating the design work and building the dashboards. This step was to optimize the report to reduce the report/file size. This is an important step which helps in reducing the file size so that is easy to share and access by users.

##Building The Dashboard
I have created 5 different report views in this report which serves the need of various stakeholders. Let’s have a look at each of them.

The first page of the report is a home page with the navigation to all other views and a summary of each page so a user can directly access the report they need to look at.

## Finance View

[Finance View](https://github.com/Raghav-026/Atliq-Business-Insight-360/blob/main/Atliq%20BI360%20Finance%20View.png)

The Finance View shows the P & L statements. The Top Performing and Bottom Performing products and customers. Different product segment performances in different regions. The most important metric here is it shows the Year on Year comparison of P & L in a single view.

There is one button created for this view which displays the Net Sales performance Vs Last Year and Vs Target. This helps in  decision-making by comparing past performance with the target to achieve the desired goals.

## Sales View

[Sales View](https://github.com/Raghav-026/Atliq-Business-Insight-360/blob/main/Atliq%20BI360%20Sales%20View.png)

The sales view is for the sales team to drill down the performance of each product and customer in individual regions. Similar to the finance view it does have the same filters to provide in-depth analysis of sales performance.

## Marketing View

[Marketing View](https://github.com/Raghav-026/Atliq-Business-Insight-360/blob/main/Atliq%20BI360%20Marketing%20View.png)

Marketing View contains Gross Margin %, Net Profit %, Operational Expenses and Cost Of Goods Sold which are important financial stats that marketing should be aware of. This helps in deciding the marketing budget for each product in a particular market. Marketing will also be aware of the potential customers and potential market and whether there is a scope for business or not.

## Supply Chain View

[Supply Chain View](https://github.com/Raghav-026/Atliq-Business-Insight-360/blob/main/Atliq%20BI360%20Supply%20chain%20View.png)

The supply chain is also a very important part of any business which if not planned timely can increase the operating cost. Keeping an inventory involves some cost and similarly not having an inventory and not delivering the products on time can harm the business.

The supply chain team should know about the demand for the products from time to time. So the historical data helps them in making informed  decisions. The visual above shows that the forecast accuracy of 80.26% in the first Quarter of the year 2020 was not good as compared to the 85.92% forecast accuracy of the same period in the year 2019.

## Executive View

[Executive View](https://github.com/Raghav-026/Atliq-Business-Insight-360/blob/main/Atliq%20BI360%20Excutive%20View.png)

The Executive view is a consolidated report which includes KIPs like NS, RC%, GM%, NP%, Forecast Accuracy%, Market share and top-selling products and top customers. This view has almost all the important metrics in one view which a top stakeholder will like to see.

An executive view saves the time of senior stakeholders who do not want to go in depth about everything but also want to keep abreast with what’s going on in every department.

# Tools Used In Project
MS Excel
MySQL
Power BI
Power BI Service
DAX Studio
## Learnings From Project
Power BI
Data Modelling
Dashboard Creation & Designing
Project Charter
Stakeholder Mapping
Going through P&L Statements
Working on business transactions like creating Profit %, Gross Margin %, Forecast %, comparison in sales from previous periods etc. (All listed below in the DAX Formulas list)
The learning from this project was not limited to Power BI. The project has a business scenario where one has to go through the P & L statements where we needed to compare the performance of the products, product categories, markets, customers etc.

From providing the stats of finance to the performance of products in different markets among different customers is measured and displayed on the dashboards.

## Power BI Features Learned & Used
DAX Formulas (Listed at the bottom)
Data Modeling
Table Creation
Creating Tool Tips
Creating Switch using Bookmark
Creating Dynamic Titles
Learnt using conditional formatting for the blank results after applying filters
Creating Dynamic Last Refresh Date
Creation Of Different Views in a single report for different departments


