# Kickstarting with Excel
## Overview of Project
### Purpose
Louise has asked for my help to compare the fundraising performance of her play, Fever, to those of other plays. I have reviewed the kickstarter data for 1,369 theater campaigns, of which 1,046 of them were for plays. I've analyzed the kickstarter data and made several recommendations for Louise to use.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/88349443/130373609-18d852a6-2c18-4bec-852d-0609f3d5bfd9.png)

This graph displays the outcome of all of theater kickstarter campaigns based on the month they were launched. The data spans several years and contains theater campaigns for plays, spaces, and musicals. 

The data in the graph shows that the launch month that resulted in the highest number of successful theater campaigns was in May. However, this graph can be misleading for a few reasons. First, it includes all theater data, when Louise is only interested in a subset, plays. Including the other subcategories in this analysis can skew the data, and it would be more accurate to remove the spaces and musicals from this dataset. Second, the graph only displays the total number of campaigns. It would be better to display the percentage successful, because it appears that May is, in general, a popular month to launch campaigns as there’s also the highest number of failed campaigns that were launched in May.
### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/88349443/130373612-48d7007d-752e-43f5-9490-34956d7b47ee.png)

The above graph displays the percentage of campaigns for theater plays that were successful, failed, and canceled based on the goal amount. 

Based on this graph, we can conclude that the highest chance of having a successful theater play campaign would be the set the goal at less than $1,000. At this goal, she would have about a 76% chance of being successful. However, it is important to understand how much money Louise needed to actually be able to start her play. If she set the goal at less than $1,000 but won’t actually be successful unless she receives at least $35,000, then I would recommend that she set the goal between $35,000 and $45,000. This range still has a fairly high success rate compared to the entire data set at 67% successful, and a low comparative failure rate of only 33%.
### Challenges and Difficulties Encountered
One challenge with analyzing this dataset is that it is unclear whether the goal amount is all in USD, or in the currency listed. If in the currency listed, then the goal amounts would need to be updated to all reflect one currency, preferably using the conversion rate at the time the campaign was launched. This could alter the results of the analysis based on goals.

Another challenge with analyzing the dataset is that only one factor was taken into account each time. It would be a good idea to also perform a multivariate analysis, to better determine the combination of factors that could result in the highest chance of a successful campaign raising enough funds to support the project. I would recommend initially including in the analysis the goal amount, length of campaign, number of backers, average donation, and staff pick as the variables, and then eliminating those with no correlation to whether or not a campaign was successful. 

Lastly, as mentioned earlier, it is difficult to perform an analysis without understanding more about the play that Louise is raising money for. For example, how much time she has to raise money and exactly how much she needs to be able to start the play.
## Results
### Outcomes Based on Launch Date Results
The Outcomes Based on Launch Date graph shows us that the best month to launch a theater campaign is in May, in order to have the highest chance of launching a successful campaign. Even though this month also has the highest number of failed campaigns, the success to failure rate is the highest of any month. Additionally, the worst month to launch would be December. Launching during this month has historically resulted in an almost an equal amount of successful and failed campaigns. 
### Outcomes Based on Goals Results
The Outcomes Based on Goals graph shows us that a theater play campaign would have the highest chance of success with a goal of less than $1,000. Additionally, a campaign with a goal of more than $45,000 is almost certain to fail.
### Limitations and Challenges of the Dataset
One limitation of this dataset is that there are several data points outside of 1.5 times the IQR. If Louise’s goal is within the IQR, it would be good to do a second graph for the Outcomes Based on Goals with a smaller range for each group. The fact that the first and second groups contain 76% of the data make the analysis of this chart unmeaningful. One challenge I had with the data set is that there is no information about whether or not the plays themselves were successful. It would be very interesting to know the ultimate success rate of plays based on how much was funded through kickstarter.
### Recommendations
I would recommend redoing the existing graphs with some minor changes including removing the canceled data. This does not give us any additional information and only makes the graphs more cluttered and confusing to read. Additionally, I would show only the theater play campaigns in the first graph and would filter for the appropriate region on both. This would make the conclusions deduced in these graphs more valuable. Additionally, I would add a graph that shows how much was pledged as a percent of the total goal for all successful campaigns, for each goal range. This could give us a better understanding of whether having a lower goal and being successful would even matter if the goal isn’t close to the actual required amount for the play.
