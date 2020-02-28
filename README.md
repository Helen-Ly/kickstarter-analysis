# An Analysis of Kickstarter Campaigns

Analzying kickstarter data to understand what factors lead to a higher rate of success for a theatre kickstarter campaign. We narrowed down the search to the U.S. and we see that, in the first graph, a good time to start a campaign would be in Qtr 2 (roughly around June). The number of successful projects decreases as their launch date starts closer to the end of the year. In the second graph, we are able to see that there are more successful campaigns for theatre.

![](https://github.com/Helen-Ly/kickstarter-analysis/blob/master/Outcomes%20Based%20on%20Launch%20Date.png)

![](https://github.com/Helen-Ly/kickstarter-analysis/blob/master/Parent%20Category%20Outcomes.png)

We have found the country, category and when the launch date should be. Now, let us take a closer look at what is an attainable budget for a theatre campaign.

|         |	Successful	| Failed |
----------|-------------|--------|
|Mean Goal|	  $5,049| $10,554|
|Median Goal| $3,000|  $5,000|
|Standard Deviation of Goal|	$7,749|	$21,968|
|Upper Quartile of Goal|	$5,000|	$10,000|
|Lower Quartile of Goal|	$1,500|$2,000|
|IQR of Goal|	$3,500|	$8,000|
|           |       |       |    		
|Mean Pledged|	$5,602|	$559|
|Median Pledged|	$3,168|	$103|
|Standard Deviation of Pledged|	$8,335|	$1,331|
|Upper Quartile of Pledged|	$5,699|	$501|
|Lower Quartile of Pledged|	$1,717|	$9|
|IQR of Pledged|	$3,982|	$492|


As we take a closer look at the table above, the mean for both goal and pledged are greater than the median. This means that the distribution is skewed more to the left. As such, campaigns with a higher goal has a higher chance for failure.

### Recommendations
For a higher chance of a successful kickstarter, we advise the following:
* Start the campaign in June
* Theatre campaigns are more successful
* Have you goal under $10,000.00


### Challenge
We further analyzed the data set to determine the following things:

* How many other Kickstarter campaigns were able to fundraise their goal in a short amount of time?
* Whether the length of a campaign contributes to its ultimate success or failure.

Two graphs were pulled from this data to take a further look:

![](https://github.com/Helen-Ly/kickstarter-analysis/blob/master/Outcomes%20Based%20on%20Launch%20Date%20(Theatre).png)

![1](https://github.com/Helen-Ly/kickstarter-analysis/blob/master/Campaign%20Outcome%20vs%20Goal%20Amount%20by%20%25%20(Plays).png)

At a quick glance, the first graph shows that launching a campaign during Qtr2 and Qtr 3 equates to the highest amount of successful campaigns. As such, one will come to the conclusion that the best time to launch is Quarter 2 beacuse the rate starts dropping after Quarter 3. This means that it will not be wise to launch any campaigns near the end of the year. The second graph shows the relationship between campaign outcomes and the goal amount by percentage. Initially, you see that campaigns with lower goal amounts have a higher success rate versus ones with goal amounts $50,000 or more.

#### Limitations
We run into issues when we want to know specifically which months are best for the launch date, the length and if that contributes to the success of a campaign. As well, are the successful campaigns exclusively within a certain country or if it is spread across the world. 


We can get a better insight by diving deeper into the data with the following graphs below:

**1. Campaign Outcome vs. Campaign Length (Plays)**

Answering if the length of a campaign contributes to its success, we did some simple math and subtracted the end date from the launch date of every campaign for plays. First looking at the graph by %, generally, there are more successful campaigns than failed ones. However, if we took a look at the second graph, it provides us with more information.

In the first graph, you don't see how many campaigns are under each category, but when you look at the actual number of campaigns as opposed to by percentage, the majority of campaigns have a length of 21 to 30 days. This is extremely important as it provides insight to why campaigns with 51 or more days have a 100% success rate. When you compare this data point to the second graph, there are a little over 50 campaigns with that length as opposed to 350 campaigns for 21 to 30 days.

![](https://github.com/Helen-Ly/kickstarter-analysis/blob/master/Campaign%20Outcome%20vs%20Campaign%20Length%20by%20%25%20(Plays).png)
![](https://github.com/Helen-Ly/kickstarter-analysis/blob/master/Campaign%20Outcome%20vs%20Campaign%20Length%20(Plays).png)


**2. Outcome Based on Launch Date**

As mentioned before, Qrt2 and Qrt3 is a good time to launch a campaign. But can we narrow that down to a specific month? Below, we are showing the same chart but by month.

The highest peak on this graph is in August, so some may conclude that launching a campaign in August will have the highest chance for success.

Another way to look at it is the overall points within a Quarter. Quarter 2 has a more consistent rate for successful and failed campaigns, as opposed to Quarter 3, where there is an increase in the successful campaigns in August and then a steep drop leading up to September. 

![](https://github.com/Helen-Ly/kickstarter-analysis/blob/master/Outcomes%20Based%20on%20Launch%20Date%20by%20Month%20(Theatre).png)


**3. Campaign Outcome vs. Goal Amount (Plays)**

Another possible limitation is if these successful campaigns are spread across the world or if it is more centralized in one country. The graph titled *Campaign Outcome vs. Goal Amount by Percentage* shows a high percent of successful campaigns with a goal amount of $4,999 and under. The next peak would be between $35,000 to $44,999. The question then becomes, how many are in each category and where are these campaigns being launched? 

In this first graph, we wanted to identify if the number of campaigns are evenly spread apart.

As we can see, majority of the campaigns fall within the $1,000 to $4,999 range and there are way below 50 campaigns that fall within the $35,000 to $44,999 range. This provides a clear picture that the graph is more left-skewed.

![](https://github.com/Helen-Ly/kickstarter-analysis/blob/master/Campaign%20Outcome%20vs%20Goal%20Amount%20(Plays).png)

Our next question can be answered in the graph below.

We filtered out the graph to strictly U.S. campaigns. We see similarities between the two graphs. Both are left-skewed and based on the number of successful campaigns in U.S., the data shows that more than half of the successful campaigns are launched in U.S.

![](https://github.com/Helen-Ly/kickstarter-analysis/blob/master/Campaign%20Outcome%20vs%20Goal%20Amount%20(US-Plays).png)


#### Conclusion

There will always be limitations as we cannot thoroughly analyze everything. However, diving deep into the data, we were able to answer our questions and tackle a few identified limitations:

1. Length may contribute to its ultimate success and failure as the highest number of successful campaigns were about 21 to 30 days in length.
2. Roughly over 350 campaigns that ran for the length mentioned above were successful.
3. We believe the best time to launch a campaign would be in June because of what happens in the following two months. The number of succesful campaigns increases to its peak and the number of failed campaigns continue to drop. This allows us to assume that campaigns are  gaining more attention resulting to an increase in exposure to this supply of backers for the ones lauching in June.
4. If you are planning to launch your campaign for a play, a good location would be the U.S. as they have more than half the amount of successful campaigns.
