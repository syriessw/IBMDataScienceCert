# Data Visualisation with Plotly and Dash

The aim of these exercise is to create an interactive report using Dash and Plotly libraries. At the end of exercise, the final report would be based on historical Automobile Sales dated between 1980 and 2013.

For the exercises, we have Airline data and Historical Wildfires.

## Data Description
The dataset includes the following variables:
1. **Date**: The date of the observation.
2. **Recession**: A binary variable indicating a recession period; 1 means a recession, and 0 means it was normal.
3. **Automobile_Sales**: The number of vehicles sold during the period.
4. **GDP**: The per capita GDP value in USD.
5. **Unemployment_Rate**: The monthly unemployment rate.
6. **Consumer_Confidence**: A synthetic index representing consumer confidence, which can impact consumer spending and automobile purchases.
7. **Seasonality_Weight**: The weight representing the seasonality effect on automobile sales during the period.
8. **Price**: The average vehicle price during the period.
9. **Advertising_Expenditure**: The advertising expenditure of the company.
10. **Vehicle_Type**: The type of vehicles sold; Supperminicar, Smallfamiliycar, Mediumfamilycar, Executivecar, Sports.
11. **Competition**: The measure of competition in the market, such as the number of competitors or market share of major manufacturers.
12. **Month**: Month of the observation extracted from Date.
13. **Year**: Year of the observation extracted from Date.

## Installation

To start, you need to install the setup tools, packaging, pandas and dash:

```bash
pip3.8 install setuptools
```
```
python3.8 -m pip install packaging
```
```
python3.8 -m pip install pandas dash
```
```
pip install more-itertools
```

## Overview

The report will serves to answer the following:

#### 1. Yearly Automobile Sales Statistics
- **Yearly Automobile Sales** - line chart displaying the average automobile sales for each year across the entire period
- **Total Monthly Automobile Sales** - line chart displaying the total monthly automobile sales for the selected year
- **Average Vehicles Sold by Vehicle Type in the Selected Year** - bar chart showing the average number of vehicles sold for each vehicle type in the selected year.
- **Total Advertisement Expenditure for Each Vehicle** - pie chart showing total advertising expenditure for each vehicle type in the selected year.

#### 2. Recession Period Statistics
- **Average Automobile Sales Fluctuation Over Recession Period** - line chart showing average automobile sales for each year during recession periods
- **Average Number of Vehicles Sold by Vehicle Types** - bar chart displaying average number of vehicles sold for each vehicle type during recession periods
- **Total Expenditure Share By Vehicle Type During Recessions** - pie chart representing the total advertising expenditure share by vehicle type during recession periods
- **Effect of Unmployment Rate on Vehicle Type and Sales** - bar chart showing effect of unemployment rate on automobile sales by vehicle type during recession periods.

## Contributing

Dr. Pooja from IBM SkillsNetwork
