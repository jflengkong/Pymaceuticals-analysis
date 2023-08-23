# Pymaceuticals-challenge
Week 5 UWA challenge

You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumours received treatment with a range of drug regimens. Over the course of 45 days, tumour development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results. 

Included in this analysis are the following: 
## Generating Summary Statistics 
Here we created a DataFrame of summary statistics including the mean, median, variance, standard deviation, and SEM of the tumour volume. This was completed by using the individual functions .mean(), .median(), .var(), .std() and sem()
![summary_statistics](https://github.com/jflengkong/Pymaceuticals-challenge/blob/main/Screenshots/summary_statistics.png)

## Creating Bar Charts and Pie Graphs 
Two identical pie graphs and two identical bar graphs were generated with the difference of using matplotlib vs. pandas. 

![bar_chart](https://github.com/jflengkong/Pymaceuticals-challenge/blob/main/Screenshots/bar_chart.png)

## Calculations for Quartiles, Outliers and Creating a Box Plot 
The final tumour volume of each mouse across the four most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin were calculated.
The quartiles and IQR were calculated and outliers were identified across all four treatment regimen. 
Groupby, merge and for loops were used to generate the desired outcome.

![box_plot](https://github.com/jflengkong/Pymaceuticals-challenge/blob/main/Screenshots/box_plots.png)

## Line Plot and Scatter Plot 
A single mouse was chosen that was treated with Capomulin and a line plot of tumour volume versus timepoint for that mouse was generate. 
A scatter plot was then generated for the entire Capomulin treatment regimen. 
![line_chart](https://github.com/jflengkong/Pymaceuticals-challenge/blob/main/Screenshots/line_chart.png)
![scatter](https://github.com/jflengkong/Pymaceuticals-challenge/blob/main/Screenshots/scatter_plot.png)

## Correlation and Regression calculations
The correlation efficient and linear regression model between the mouse weight and average observed tumour volume for the entire Capomulin treatment regime was calculated. 
This was then plotted against the scatter plot. 
![regression](https://github.com/jflengkong/Pymaceuticals-challenge/blob/main/Screenshots/correlation_plot.png)
