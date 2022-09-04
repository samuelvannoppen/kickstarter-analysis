# kickstarter-analysis

## Overview of Project
Performing analysis on Kickstarter data to uncover trends for the use of a crowdfunding campaign for a theatre preformance.

### Purpose
Helping an up-and-coming playwright, Louise, who would like to start a crowdfunding campaign to help fund her play, *Fever*. She's estimating a budget of over $10,000 and has been hesitant about jumping into her first fundraising campaign. Excel has been used to organize, sort, and analyze crowdfunding data to determine whether there are specific factors that make a project's campaign successful.

## Analysis and Challanges 

### Analysis of Outcomes Based on Launch Date

The data was first formatted to be easier to use and find note-worthy analysis for theatre Kickstarters. The data was then further concentrated on plays subcategory. This was done by creating several pivot tables. The data was filtered into parent categories. Subcategory filters was placed in the table. The projects were filtered by location, outcomes, successful, failed, live, and cancelled. This allowing to see when Louise could run her project and for how long to best encounter successful results.

![Theatre_Outcomes_vs_Launch](https://user-images.githubusercontent.com/111381326/188290265-5100cb78-fa5f-41df-8c3d-1f139fe50081.png)

![Theatre Outcomes vs Campaign Length](https://user-images.githubusercontent.com/111381326/188290267-13787cc7-aed3-444d-ad27-ad3653a35d02.png)


### Analysis of Outcomes Based on Goals

A large amount of the success of the campaigns was found in determining the original goal size. The data was formatted based upon a range of campaign goal sizes. The data was filtered just to show the data points from theatre plays. A large body of the plays fell within the category of goals of less than 1000 with a high success rate.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/111381326/188289721-b931ad01-5baf-4860-a6a5-8724f6f85527.png)

### Challenges and Difficulties Encountered

#### Data Size
A difficulty faced is that within Louise's budgeted $10000 there a limited amount of data points. There are only 23 total projects that are run within the 10000-14999 goal range with a 43% success rate. There were a large number of outliers outside of the 1st and 3rd quartiles which could have contributed.

#### Timestamps
A challenge that was faced was reformatting the UNIX epoch timestamps. As date started were needed so that trends campaigns time could be found.


![Box and Whisker Chart for Goal Outliers](https://user-images.githubusercontent.com/111381326/188289757-9495c9cb-20e5-4c15-a581-67ddc32bdfa8.png)

## Results

### Launch 

Based on the analyses it is recommended that the campaign be launched in the month of May and run for a period of 30 days to best encounter a successful crowdfunding campaign.

### Goal Size
It is recommended that fixed goal for the campaign be below the budgeted amount of $10,000. A higher level of confidence is found in the 5000 to 9999 range. Secondary funding could be found from running a second campaign or private sponsorship.

## Further Study

Further study could be done by comparing average donation size to the fixed goal in line chart. By expanding the data set. Or by testing the effectiveness of running smaller campaigns in sequence.
