# Kickstarting with Excel
### 1. Overview of Project
For this analysis, we examined a set of different crowdfunding data to help Louise start a campaign for her new play, *Fever*. She is trying to find out the likelihood of success based on her proposed budget of $10,000, so we took data from other crowdfunding campaigns to look at past trends and try to make predictions for future success.
### 2a. Analysis
We took the information in this dataset and started by formatting and cleaning the information in it to make it easier to analyze. We then took some of the information given to us and performed some calculations to analyze it further. We looked at all information for theaters and plays and narrowed it down specifically to US theater and plays data. We found that theater kickstarters were the most successful of all the categories (which is good news for Louise :+1: ). 

![image](https://user-images.githubusercontent.com/99522862/155899077-6fad7008-c769-4e0e-b949-011863d4d333.png)

We then narrowed down the theater category to US kickstarters and found them to have a large success rate, with the successful category being more than the other three categories combined.

![image](https://user-images.githubusercontent.com/99522862/155899503-2c917105-b9a2-44ea-a8ea-8aba358d2921.png)

### 2b. Challenges
Sometimes we did encounter problems. For instance, we wanted to look at the average donation by backer, so we used a formula to determine on average how much each backer donated. This led to an error because some campaigns did not have any backers, and when calculating the average, dividing by zero creates a problem. We got around this by identifying why the problem was occurring and used a specific program formula to work around this error and mark that cell as 0. 

Another challenge that I came across was fact checking that the calculations I was using in Excel were producing the correct information. This specifically came up when I was calculating the data for Outcomes Based on Goals. In the canceled column I was very alarmed at first that everything was coming up as 0. I then went back to the Kickstarter page and used the skills from previously in the module to filter the dataset for the canceled kickstarters for US plays and found that there were no canceled ones, and that is why the entire column was coming up as zero. I found that fully understanding how to filter the large dataset is a good way to check as I went that the calculations were coming out correctly.

### 3. Results
* In looking at theater outcomes based on their launch date, it is clear that Louise will find the most success by launching her campaign in either May or June. Between those two months there were 211 successful campaigns, which make up 25% of the successful campaigns for all of the months combined. From looking at this graph, it is also clear that campaigns that launch in December have an almost equal failure and success rate, so I would advise Louise to avoid launching her campaign during that month.

![image](https://user-images.githubusercontent.com/99522862/155900050-b5f0e900-8d13-4869-96cf-fcc636028734.png)

* However, once we looked at the Outcomes based on Goals data, it is clear that Louise might not find as much success with a budget of $10,000 as she would if she cut that budget in half. 73% of the projects between $1,000 and $4,999 were successful, where as only 55% of the campaigns between $5,000 and $9,999 were successful, with a much larger failure rate for the latter category. 

* A limitation of this dataset is that we cannot tell how these campaigns were advertised and what events were held or fundraisers used to help acquire backers. It might be useful to acquire that information and see if maybe some of the failed campaigns were lacking in exposure to potential backers, or identify trends that made the campaigns with the most backers successful.

* Another recommendation for analysis might include making a table to look at the goal amount versus the pledged amount for play campaigns around the budget that Louise is looking at. It might be telling to see how much more than the pledged amount was compared to the goal for the successful campaigns, or how much under the failed campaigns were. We might learn a lot more by seeing how big the difference is, and this could help us predict if Louise’s proposed budget would be close or far off from meeting the goal.
