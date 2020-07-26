# Kickstarting with Excel

## Overview of Project

Louise, an aspiring playwright successfully received funding from a fundraising campaign for her play. Now, Louise wanted to know how different campaigns in the category of theater and more specifically plays performed based on their launch dates and their funding goal. We have a dataset of past Kickstarter campaigns with various observations and measures which was utilized to analyze how such Kickstarter campaigns similar to Louise’s performed in relation to when they were launched and how much goal they set out with. This report provides analysis and visualization to summarize the deductions made from the data set on past Kickstarter Campaigns.     

### Purpose

The Purpose of the project was to help Louise understand how previous fundraising campaigns performed in relation to their launch date and funding goal by analyzing a data set on past Kickstarter campaigns similar to her campaign.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date


From the analysis of data and the line chart of outcomes based on the launch month for the theater category of Kickstarter campaigns we can see that May is the best time to launch such campaigns. Campaigns launched in September to March are the least successful. Although, there are a high number of failed campaigns in May, it could be attributed to the fact that a total of 166 theater campaigns were launched that month which is the highest across all the other months.


### Analysis of Outcomes Based on Goals
Image 2 

From the line chart on we can observe that campaigns for plays who had a goal of less than $1000 and just below $5000 were the most successful with close to having a success rate in the 70th percentile. On the other hand, plays who had a goal between $35000 and $40000 also had a good success rate close to 67%. This can indicate that other than just the fundraising goal there could be other factors that do a play an important part in having a successful campaign. The most unsuccessful campaigns are the ones who set with goals over $45,000.  


### Challenges and Difficulties Encountered

The initial data on launch date was not readable as they contained UNIX timestamps. To solve this issue the data was converted so that they represented a standard date format to better read and understand the data. Furthermore, we just needed the year to do our analysis on launch date. To solve this, the launch date column was further profiled by using the YEAR function in Excel so that we could quickly extract the data for the analysis.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

We can deduce the following conclusions from Analysis of Outcomes based on Launch Date: 
-	May is the most successful month to launch a Kickstarter campaign for a play. 
-	September to March are the least successful months to launch a campaign.

- What can you conclude about the Outcomes based on Goals?
We can deduce the following conclusions from Analysis of Outcomes based on Goals:
-	Having a low fundraising goal below $1000 has the highest success rate. 
-	Factors other than just a low goal amount also influence the success rate of the campaign as we observed that even higher goal amounts of $35000-$45000 have a high success rate. 


- What are some limitations of this dataset?

The data set is just a representation of the sample from a handful number of countries and it might not be a very accurate representation of the Kickstarter campaign data. The data set has Goal and Pledged amounts in various currencies and adjustments for the currency exchange rate has to be made to paint a more accurate picture.    

- What are some other possible tables and/or graphs that we could create?

To have a better understand the correlation of the Fundraising Goals and launch date with successful campaigns we could calculate central tendency measures such as mean, mode and median and also the spread of the data through variance and standard deviation. We can then perform a linear regression to understand fully the correlation between launch and date and goals with campaign success.  
