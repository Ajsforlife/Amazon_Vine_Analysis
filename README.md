# Amazon Vine Analysis

## Overview

### Purpose

The purpose of thise analysis was to first create an RDS on Amazon web services and import dataframes into SQL using the RDS. Second was to perform an analysis to determine if there was any benefit of vine reviews versus non-vine reviews. The datasets are massive which made the importing to SQL take almost an hour to finish. But the analysis went smoothly.

## Results
### Deliverable 1

This was the basic analysis to import the dataframes into SQL via RDS AWS the following picutres are of the dataframes created.

![image1](https://github.com/Ajsforlife/Amazon_Vine_Analysis/blob/main/challenge%20pics/deliverable%201.png)

![image2](https://github.com/Ajsforlife/Amazon_Vine_Analysis/blob/main/challenge%20pics/deliverable%201-2.png)

![image3](https://github.com/Ajsforlife/Amazon_Vine_Analysis/blob/main/challenge%20pics/3deliverable%201-2.png)

### Deliverable 2

This was the actual vine analysis performed. It let us select our dataset and I choose mobile apps. 

![image4](https://github.com/Ajsforlife/Amazon_Vine_Analysis/blob/main/challenge%20pics/deliverable%202.png)

![image5](https://github.com/Ajsforlife/Amazon_Vine_Analysis/blob/main/challenge%20pics/-2deliverable%202.png)

The mobile apps dataset has 0 paid Vine reviews mainly because I think Vine is used for video games, but I am not positive. However the total 5 star vine that had over 50% helpful_votes was 0 and the total non-vine reviews that had pver 50% helpful_votes was approximately 45.77%. Apparently I got lucky and chose the dataset with actualy vine revivews.


## Summary
In this dataset there was no bias what so ever on reviews from the vine program. Solely because vine is not used to review mobile apps. If they added mobile apps to the vine reviews this analysis would be able to determine if there was bias based on the vine app. In theory to better this analysis vine would have to add mobile apps to their reviews. However it seems that mobile apps are rated fairly at around 50% with 5 star ratings.


