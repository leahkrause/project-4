# Defense of the Heart: Predicting Heart Disease
![heart](https://consumer.healthday.com/media-library/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpbWFnZSI6Imh0dHBzOi8vYXNzZXRzLnJibC5tcy8yOTQ0NDUwMy9vcmlnaW4uanBnIiwiZXhwaXJlc19hdCI6MTcxMjExNTk2NH0.pKhuDDKlJouXcV5xb9j6Iw7b4v8DyAM5kj4gPY4mxHQ/image.jpg?width=1245&height=700&quality=85&coordinates=0%2C41%2C0%2C42)

## Introduction 
In recent years, heart disease has emerged as a major health concern worldwide. This cardiovascular condition not only poses a significant threat to individuals' well-being but also places a substantial burden on healthcare systems. To effectively address these challenges, it is crucial to gain a comprehensive understanding of the trends and correlations associated with heart disease. The objective of this project is to analyze various factors and datasets associated with cardiovascular health in order to investigate and predict underlying patterns and trends.

## Data Source, Cleaning, and Analysis
For our project, we have chosen to utilize the official website of the [Centers for Disease Control and Prevention (CDC)](https://www.cdc.gov/brfss/annual_data/annual_2021.html) as the primary source of our data. We obtained a SAS file from the CDC website, and we utilized Python for data cleaning and the creation of simplified datasets that are specifically tailored to our investigation.

One key aspect of our research focuses on the utilization of super reduced datasets, which consist of a limited number of variables. These datasets provide us with valuable insights into heart disease by examining factors such as cigarette usage, work status, and gender. By studying the relationships between these variables and the incidence of heart disease, we aim to gain a better understanding of how they interact with cardiovascular health.

## Machine Learning - Correlation and Findings

## Overview

## Design an Interactive DashBoard
We used Tableau to design and create our interactive dashboard. Dimensions are selected according to their correlation with the target variable(Heart Disease). Based on these particular parameters' values, the user can apply a corresponding filter. As shown in the following figures, we designed two separated pages for our dashboard. 
The Main Page includes all the demographic characteristics of data including *age, gender, work status, marital status, and education*. Some of the other features which correspond to health conditions like *Physical/Mental Health, Routine checkup, Cholesterol, Diabetes,..* are also available as a different set of filters. In the Main Page, the user can compare two groups which are tagged as Having Heart Disease/Not Having Heart Disease. 


![Main Page](images/Heart_disease_dashboard.png)


The Second Page includes more detailed information of people who are having heart disease.
The user can switch between the Main and Second page using the provided buttons at the top of the page.

![Main Page](images/Heart_disease_group.png)
