# -Aerofit-Treadmill-Customer-Analysis
# Aerofit Treadmill Customer Analysis

## Overview

This repository contains an analysis of customer data for Aerofit, a fitness equipment brand. The goal of this project is to understand the characteristics of customers who purchase different treadmill models (KP281, KP481, and KP781) to help Aerofit provide better recommendations to new customers.

## Business Problem

The market research team at Aerofit aims to identify the target audience characteristics for each treadmill type to improve customer recommendations. ]The analysis investigates differences in customer characteristics across the various product lines

## Dataset

The dataset contains information on individuals who purchased an Aerofit treadmill in the prior three months

### Features:
**Product Purchased**: KP281 (entry-level), KP481 (mid-level), or KP781 (advanced) 
**Age**: In years
**Gender**: Male/Female 
**Education**: In years 
**MaritalStatus**: Single or Partnered
**Usage**: Average number of times the customer plans to use the treadmill each week
**Income**: Annual income (in $) 
**Fitness**: Self-rated fitness on a 1-to-5 scale (1: poor, 5: excellent) 
**Miles**: Average number of miles the customer expects to walk/run each week 

### Product Portfolio:
**KP281**: Entry-level treadmill, sells for \$1,500 
**KP481**: Mid-level treadmill, sells for \$1,750 
**KP781**: Advanced features treadmill, sells for \$2,500 

## Analysis Performed

### Data Loading and Inspection
The dataset `aerofit_treadmill.csv` was loaded using pandas
Initial inspection of the data shape revealed 180 entries and 9 columns
Data types and non-null counts were checked, showing no missing values

### Descriptive Analytics
Descriptive statistics were generated for numerical features such as Age, Income, Miles, Education, Usage, and Fitnes

#### Key Observations:
**Age**: The average age of customers is approximately 28.79 years, with a minimum of 18 and a maximum of 50 yearsThe most frequent age for customers is 25 years
**Income**: The average annual income is about \$53,719.58
**Miles**: Customers expect to walk/run an average of 103.19 miles per week
**Education**: The average education level is around 15.57 years
**Usage**: Customers plan to use the treadmill an average of 3.46 times per week
**Fitness**: The average self-rated fitness level is 3.31 on a 1-to-5 scale

### Non-Graphical Analysis (Value Counts and Unique Attributes)
* **Product Distribution**:
    KP281: 80 customers 
    KP481: 60 customers 
    KP781: 40 customers 
* **Gender Distribution**:
    Male: ~57.78% 
    Female: ~42.22%
* **Marital Status Distribution**:
    Partnered: 107 customers 
    Single: 73 customers 

### Visualizations
Various plots were generated to visualize the distribution of customer characteristics:
**Age Distribution**: A count plot shows the frequency of customers across different age groups, highlighting that ages 23, 24, 25, and 26 have higher counts
**Income Distribution**: A box plot for Income illustrates its spread and identifies potential outliers
**Age vs. Education**: A line plot shows the mean education qualification across different age groups
**Age vs. Miles by Marital Status**: A scatter plot visualizes the relationship between age and expected miles, differentiated by marital status
**Gender Distribution**: A pie chart illustrates the proportion of male and female customers
**Product Sales Count**: A count plot displays the total number of units sold for each product
**Product Sales by Gender**: A grouped bar chart shows the sales count for each product, broken down by gender

## Next Steps

The next steps in the analysis involve:
* Constructing two-way contingency tables for each Aerofit treadmill product.
* Computing all conditional and marginal probabilities from these tables.
Deriving insights and impacts on the business from these probabilities to create comprehensive customer profiles for each treadmill product[cite: 8].
