# Overview

"Power Bi project showcasing  for global superstore dataset.This project provide report of sales transactions, shipping trends, and market analysis .It include various visualization helps to stakeholders".

## Table of Contents
1. [Getting started](#)
2. [Data Cleaning Steps](#data-cleaning-steps)
3. [Visualization Segmentation](#)
4. [Sales Visulization](#)
5. [Tables](#)


## Getting started:
 To started with Power Bi project:
 1. Download the the file from the given below
 [https://docs.google.com/spreadsheets/d/1zNWOWH3T_KllALPDvWv-Jcqtwz4T9TpQ/edit?gid=1807457842#gid=1807457842]
 2. Open the file using Power BI Desktop.
 3. Explore the various visualizations and tables to gain insights into sales transactions.

## Data Cleaning: 
The dataset basic data cleaning to ensure accuracy and consistency. Cleaning steps include correcting the column headers,removing duplicates ,null values etc.

## Visualization for Analysis:
Segment the visuals using country, region, market: 
Analyze the data by visualizing the percentage of shipping based on ship mode.

## Shipping Analysis:
Shipping Percentage by Ship Mode:
A DAX formula has been applied to calculate the percentage of shipping costs based on ship mode.
         DIVIDE(SUM('Orders'[Shipping Cost]), CALCULATE(SUM('Orders'[Shipping Cost]), ALL('Orders'[Ship Mode])))

## Sales visualizations:
* Sales by Region (Map):
Use the map visualization to visually represent sales across different regions.
* Sales by City (Stacked Column Chart):
Analyze sales trends in various cities using the stacked column chart.
* Sales by State (Map):
Visualize sales distribution across different states using the map.
* .Sales by Market (Stacked Bar Chart):
Understand sales performance by market through the stacked bar chart.different graphs.

## Table:
Created based on each visualization.
