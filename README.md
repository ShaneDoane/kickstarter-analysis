# kickstarter-analysis

## Overview of Project
Analysis of different Kickstarter projects from various countries

### Purpose
Identify trends in previous kickstarters to provide insight relevant to Louise's campaign to optimize decision making and ensure success

## Analysis and Challenges

*Analysis: conducted on a Kickstarter dataset. PivotTables and PivotCharts were the primary tools for gleaning insights. Example of dataset below. 
<img width="1434" alt="image" src="https://user-images.githubusercontent.com/93338132/147302467-b0b21511-0c0c-42c8-ab47-74e188d96af7.png">

*Challenges: Unix timestamps were converted to human-readable date format. Category was split into Parent & Subcategory format to further delineate. No significant challenges otherwise.

### Analysis of Outcomes Based on Launch Date
*More total campaigns are launched in ~April to July timeframe
*More successful campaigns both in absolute terms and as percent of total
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/93338132/147302977-24c6a16d-bf5b-4bcc-beae-6c2d941f9ccb.png)


### Analysis of Outcomes Based on Goals
Success is negatively correlated with goal size. I.e. risk of failure rises with goal size in Dollars.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/93338132/147302981-72de9837-15f7-479a-a293-289173cea83b.png)

### Limiations of Dataset
*No explanation of 'Spotlight' or 'Staff_pick' variables
*Limited sample size of campaigns in 'Plays' subcategory with goals above $15,000


## Other Potential Analyses
*View the previously analyzed trends for different years
*View previous trends by year
*Incorporate 'Staff_pick' or 'Spotlight' variables into analysis
*Explore relationship between count of donors and success of campaign
