# Terrorism_Analytics

A D3-based interactive visual interface which would allow users to gain insight on terrorist activities around the world.  
Technology: Python, D3, HTML, CSS, JQuery. 

The major highlights are –
* Prediction of casualties using decision tree model 
* Dataset of size more then 180000 which includes Data Cleaning, Dimension Reduction, Text mining

## Installation Requirements: 
Python, IDE(Pycharm or Atom preferably)
Libraries:
Python - seaborn, matplotlib, pandas, numpy, nltk, scipy, wordcloud, flask, sklearn, json, plotly 
External Libraries – D3.js, Jquery

## Data Selection and Description:
* Spatio-Temporal Variables:
where in time and space was the act ofterrorism committed? 'iyear', 'imonth', 'iday', 'latitude', 'longitude',
* Binary Variables:
'crit1', 'crit2', 'crit3', #The incident meets the criterion (1, 2, 3), described in the introduction
* Continuous Variables:
'nkill', #Amount of confirmed kills 'nwound', #Amount of confirmed wounded
* Categorical Variables:
'country_txt', #Name of country
'region_txt', #Name of region
‘city’, # Name of city
'attacktype1_txt', #Of what type was the attack? I.e. assassination, bombing or kidnapping 'targtype1_txt', #What target did the attack have? I.e. business, government or police 'weaptype1_txt', #What weapon was used?
* Descriptive Variables:
'target1', #Description of specific target, if applicable 'gname', #Name of the organized group, if applicable

## Data cleaning:
Below optimizations were used to clean the data:
* Random acts of violence and other outliers should not be part of the data. Thus, we rest-
ricted the data to contain only attacks where the terrorism motive is certain
* Shortening long text for the string columns like – Weapontype
* Ensuring the consistent values and making everything lowercase
* Replacing some NaN values by their median like - nwound and nkill

## Data Exploration:
Some Basic Analysis:
* Country with Highest Terrorist Attacks: Iraq
* Regions with Highest Terrorist Attacks: Middle East & North Africa 
* Maximum people killed in an attack are: 1384 that took place in United States

## Areas Covered:
1. Charts like Pie-charts, barcharts, line-charts, donut- charts etc for various categories like: Number of terror attacks per year, Successful and Failed attacks, Types of attacks, Types of targets, Regions affected mostly by what kind of attacks, Groups which have attacked the most in that particular decade
2. Human freedom index change over the years with respect to different regions.
3. How terrorism is also affecting the human freedom index
4. Map visualization for different categories like: Locations with maximum attacks.
5. Word cloud to highlight the motivation of attackers

![Image of kaggle](https://github.com/PoojaAg18/Terrorism_Analytics/blob/master/data/kaggle.png)

