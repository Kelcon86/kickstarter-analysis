# Kickstarter-Analysis

## Overview of Project

### Purpose
Analysis was performed on kickstarter crowdfunding data to uncover trends and determine if there are specific factors that make a projects campaign successful in order to help a playwright determine the best approach to her fundraising campaign.

### Background
Louise is an up-and-coming playwright who is looking to start a crowdfunding campaign to fund her play "Fever". She is estimating a budget of over $10,000, but is hesitant to begin her first crowdfunding campaign and would like an Excel power user to help analyze crowdfunding data.

## Project Analysis 
Analysis was performed by creating a pivot table and chart to examine the outcome of theater kickstarters based on the launch date as well as the outcome of kickstarters from the play subcategory based on monetary goals. 

### Analysis of Outcome Based on Launch Date
In order to determine the outcome of theater campaigns based on the launch date we first created a years column in the Kickstarter spreadsheet. We then created a pivot table labeled "Theater Outcomes by Launch Date and filtered the table on "Parent Category" and "Years". The row labels were changed to display the months of the year and campaign outcomes were sorted in descending order. A line chart was then created to show the number of successful, failed and canceled projects by month.

![PivotTable](https://user-images.githubusercontent.com/60076980/148302719-06009a2a-e3b5-4511-92f2-e909451a77ad.png)
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/60076980/147240461-b1e783ff-1529-41c9-9623-cc6edbd75c2b.png)

### Analysis of Outcomes Based on Goals
In order to determine the outcome of campaigns in the plays subcategory we created a new sheet labeled Outcomes Based on Goals and used the COUNTIFS() function to show the number of successful, failed and canceled campaigns based on their goal amount. The SUM function was usesd on each row to populate the total projects column and percentages were calculated based on the data from the "Total Projects", "Number Successful", "Number Failed" and "Number Canceled" columns. A line chart was then created with the goal amount on the x-axis and the percentage of successful, failed or canceled projects on the y-axis.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/60076980/147471797-0b5009f0-97e2-4f7b-8bb7-6797c9f0f92e.png)

## Challenges
The main challenge that I encountered was in deciding which PivotTable Fields to place in the Filters, Columns, Rows and Values area in order to best visualize the data. Through trial and error I was able to create a table and chart that nicely visualized the number of successful, failed and canceled theater projects based on their launch date.

## Results
Analysis showed that theater kickstarters that were launched in May and June had the most successful outcomes. Theater kickstarters that were launched in December had the lowest success rate. 

Kickstarters that had a goal greater than 50,000 had a fail rate of 99%. Of the kickstarter projects in the plays subcategory 39% had a goal between 1000 and 4999 and the success rate for those projects was 73%.

Some of the limitations with this dataset is that all of the data for plays is from a 7 year span between 2010 and 2017, with the vast majority of the play campaigns occurring between 2014 and 2017. It would be helpful to have more current data to see if these trends have changed in recent years. We also were limited to data exclusively from Kickstarter. It would be interesting to see if other crowdsourcing websites showed similar results.

There are numerous other tables and graphs that could be created from this dataset. We focused on the theater parent category, but we could explore the data from various other categories to see if the outcomes based on launch date and goals were similar. We could even analyze the data from the entire dataset to see if there were trends similar to what we saw in the plays subcategory.

