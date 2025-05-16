# Tata-Data-Visualizations-Virtual-Internship
This repository holds all of the completes tasks I was needed to complete for the TATA Data Visualization Empowering Business with Effective Insights Virtual Experience Program
## 1. Project Background:
An online retail store hired me as a data analytics consultant to help them understand what’s driving their sales and customer behavior. The goal was to give insights to the CEO and CMO so they can make smart decisions about growth and marketing strategies. 

## 2. Deliverables:
(a)Key questions from CEO and CMO perspectives

(b)Visual selections and their creations

(c)Insights and recommendations based on the Data Analysis

## 3. Skills Utilized:
(a) Data Analysis

(b) Data Modeling

(c) Data Visualization

(d) Project Planning

(e) Presentation

(f) Strategy

## TASK 1: UNDERSTANDING THE PROBLEM
I was tasked to draft 8 key questions — 4 for the CEO and 4 for the CMO — that I anticipate they will ask based on the dataset provided. These questions were to guide my presentation and analysis.

CEO Questions (Business Focus):

(a) Which product categories and regions generate the most revenue?

(b) What are the trends in sales and profit over time?

(c) Which customer segments bring in the most value?

(d) Where should we expand next based on performance?

CMO Questions (Marketing Focus):

(a) Which marketing channels drive the most conversions?

(b) What do loyal/high-value customers have in common?

(c) What campaigns increased engagement or sales?

(d) How do different demographics respond to marketing?

## TASK 2: DATA CLEANUP, DATA MODELLING AND CHOOSING THE RIGHT VISUALS
(i) Data Cleanup:

The original dataset included:

- Negative quantities indicating product returns

- Negative unit prices, likely due to manual data entry errors

so to clean the data I ...

- Excluded rows with Quantity < 1
These represent returns or errors. Kept only sales with at least 1 unit purchased.

- Excluded rows with Unit Price < 0
Negative prices are invalid for analysis and likely input mistakes

(ii) Data Modelling

After cleaning, I transformed the dataset to support analysis by calculating the Revenue.
I inputed this in power query for PowerBI:

Revenue = Quantity × Unit Price

(iii) Choosing the right visuals

The Summary of Executive Questions by the CEO and CMO that helped me choose the visuals to use for the analysis:

- CEO – Monthly Revenue Trends (2011)
Wants to see monthly revenue trends for 2011 to identify seasonal patterns and support future forecasting. Chose a line chart

- CMO – Top 10 Countries (Excluding UK)
Needs a view of the top 10 revenue-generating countries (excluding the UK), with both revenue and quantity sold for marketing insights. Chose a Stacked Column chart

- CMO – Top 10 Customers by Revenue
Wants a chart showing the top 10 customers by revenue, sorted from highest to lowest, to help target and retain high-value customers. Chose a Stacked Column chart

- CEO – Product Demand by Country (Excluding UK)
Needs a single-view visual showing demand (quantity sold) across all countries (excluding UK) to identify expansion opportunities. Chose a Map

## TASK 3: VISUAL CREATIONS
After choosing the visuals I made the data Visualizations in PowerBI. Below are the images of the visualizations:



## TASK 4: COMMUNICATING INSIGHTS AND ANALYSIS
After making the visuals, I presented my findings to the CEO and CMO.  Below is the video:

## Certificate of Completion









