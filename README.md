# kickstarter-analysis
An Analysis of Kickstarter Campaigns

# Kickstarting with Excel

## Overview of Project
To find correlations in Kickstarter data between launch dates of the campaigns and goals achieved. 


### Purpose
The purpose of this project was to take a large dataset and determine what trends we could observe. Working with the Kickstarter data required sorting, filtering, visual aids in the form and pivot charts and tables, vlookups as well as creating statements and nesting statements together. These tools allow us to report our findings to the stakeholder.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To start, we were given data based on past Kickstarter initiatives. From there we focused on campaigns that had to do with theater as Louise is interested in how her fundraising efforts compared. First, we created a pivot chart to easily look at the data in a structured way. Campaigns that launched in May had the greatest success with a steady decline over the months until September. January to April and September to November had similar outcomes while December had the least success. The number of canceled campaigns remained about the same every month. While the data suggests March is the most successful month to launch a campaign, this data is not conclusive and other factors should be taken into consideration.
![image](https://user-images.githubusercontent.com/89358080/130387603-968cafd9-1b9d-4345-882e-68829f68d63a.png)
  

### Analysis of Outcomes Based on Goals
The percentage of failed efforts steadily increased from 24% to 80% up until $29,999 but due to the outliers the data is actually right skewed. In actuality the majority of successful campaigns were under $25,0000 and there the data above this value are not statistically significant.
![image](https://user-images.githubusercontent.com/89358080/130387620-c13ff137-a1b5-478c-95b1-c71b88e2e1ce.png)


### Challenges and Difficulties Encountered
There were not many challenges I encountered while working with the data. I would say the most difficult portion was how repetitive and time consuming creating all the =COUNTIFS() statements. While I did not have to do any debugging it took a lot of patience and attention to detail to ensure I was selecting the appropriate columns and outcomes.

## Results

+ What are two conclusions you can draw about the Outcomes based on Launch Date?
May is the optimal month to begin Kickstarter campaign.

+What can you conclude about the Outcomes based on Goals?
Nothing as none of the currencies were standardized

+ What are some limitations of this dataset?
One limitation would be the demographics of the users, access to the campaigns, and that we did not convert currencies.

+ What are some other possible tables and/or graphs that we could create?
We could also create a box and whiskers plot to examine the effect of outliers or a histogram.


