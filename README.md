# PyBer Analysis Report

## Background and Results

### Purpose
The purpose of this assignment is to create two additional technical analyses and a written report that delivers our results to the CEO.  
### Technical Analysis
Technical Analysis Deliverable 1: A DataFrame that summarizes the key metrics for the ride-sharing data by city type. 
Technical Analysis Deliverable 2: A multiple-line chart, with one line for each city type, that shows the sum of the fares for each week. We used Pandas to create DataFrame summary for deliverable 1 and Matplotlib to plot line chart for deliverable 2.
### Results
From the Summary DataFrame Table. Urban has the highest number of total rides, drivers, and total fares but the lowest average fares per ride and average Fare per driver. Rural has the lowest number of total rides, drivers, and total fares but the highest average fares per ride and average Fare per driver. The Suburban has all the attributes values between the Rural and Urban. 

![](https://github.com/keyoumao/PyBer_Analysis/blob/master/analysis/DataFrame%20Table.PNG)

Figure of the Total Fare By City Type is fiven as follows. During the first four months of 2019 for each of the time period, Urban has the No.1 fares, Suburban has the No.2 highest and Rural has the lowest fare. 

![](https://github.com/keyoumao/PyBer_Analysis/blob/master/analysis/Fig_Challenge.png)

### Summary
The ranking of the total fares based on the City Type reveals a positive correlation between the total rides/drivers and the total fares. An inverse correlation between average fares per ride/driver and total fares is found for based on the City Type.

## Challenges Encountered and Overcome

### Challenges and Difficulties Encountered

* Programming<br />
Using the pandas.pivot_table function and combinations of loc and resample to obtain new dataframes.
* Data analysis<br />
Find the story behnd the data; clean and merge the data; find the anormalities. 
* Graphing, etc<br />
How to appropriately formatting the figure; precisely plot the dataframe. 

### Technical Analyses Used
Most of the functions we could refer to the Pandas official documentation, and instructions can also be found in the Matplotlib documentations to fulfill our requirements for plotting. Some votes answers on the stackoverflow, tech blogs, office hours and TA sessions could help solve some challenges as well. 
## Recommendations and Next Steps

### Recommendations for Future Analysis
We suggest Pyber to add more rides to the Urban and keep the rides and drivers for the rural and suburban region. Below are two more additional analyses which could help us gain more insights from our data. 
### Additional Analysis 1

* Description of Approach<br />
Find relationship the total fare basded on the each City: providing suggestions for adding/reducing rides/drivers in different cities.
* Technical Steps<br />
Create DataFrames based on each city and find if anything abnormal could be found in certain cities linked to the City Type.
### Additional Analysis 2

* Description of Approach<br />
Find relationship the total fare for a longer period of time basded on the City Type: providing suggestions for adding/reducing rides/drivers in different months.
* Technical Steps<br />
Create DataFrames groupby City Type and then focus on finding trends over a longer period of time. 


