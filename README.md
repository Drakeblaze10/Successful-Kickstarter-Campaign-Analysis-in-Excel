# Analysis of Kickstarter Outcomes Based on Launch Date and Goals

## Overview of Project

### Background
- A collection of Kickstarter Campaigns, ranging from 2009-2017. The data needs to be visualized so that the relation between launch dates and funding goals between different campaigns can be compared.
### Purpose
- The purpose of this project is o visualize and analyze Kickstarter outcomes based on launch date and goals. Using pivot tables, theater Kickstarter campaigns were filtered by their success in relation to their lauch date. C
- Using the Countifs formula to sort the outcome of kickstarter campaigns based on their goals.
- Creating line charts to visualize both sets of data.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Using pivot tables, the data was filtered by theater, and during which month they were launched, based on their outcomes. Data was sorted highest to lowest, followed up with a line chart based on the pivot table. The Line graph was finally adjusted for clarity with the inclusion of a title and readable labels.
![Chart](https://raw.githubusercontent.com/Drakeblaze10/Successful-Kickstarter-Campaign-Analysis-in-Excel/main/resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
Using the Countifs formula, data was filtered and sorted by how successful the campaign is based on their monetary goal set. It was also further filterd by plays to narrow down the focus. Once the data was organized using this format, and their total, the total percentage of successful outcome was used to create a line graph to visualize the success of a play campaign based on their monetary goals.
![Chart_Goals](https://raw.githubusercontent.com/Drakeblaze10/Successful-Kickstarter-Campaign-Analysis-in-Excel/main/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
There was a bit of a challenge with the Countifs formula, making sure the corret column was selected as well as the correct symbols for greater than less than. Need a couple of rereads on the formula to make sure its accurate.

## Results
- The dataset and the visualization of the linechart suggest that the liklihood of a successful campaigns are launched during the summer with the most successful month being May. During the winter, especially December, the liklihood of a successful campaign significantly decreases.
- The dataset and linechart suggest a higher percentage of successful campaigns if the monetary goals was less than $5000 as well as between $35000 to $449000.
- Although both datasets are specified aroung theater and plays, the dataset still remains to broad. The genre of plays as well as the country are not included. In addition the ranges between the monetary goals are also large with a range of approx. 4999, providing a wide window for a monetary goal. 
-Regarding the request of a visualization of data based on goals and Launch date, narrowing down the dataset even further by country could be helpful. 

