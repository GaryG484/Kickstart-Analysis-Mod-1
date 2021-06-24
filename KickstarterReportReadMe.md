# Fundraising on Kickstarter: How the success of a campaign is related to the initial funding goal and the date the campaign was launched. 

## Overview
##### In this project I utilized data on Kickstarter campaigns to analyze different mediums of theater.  The data encompassed many factors but the ones I focused on here included the following: the date the campaigns were launched, the initial fundraising goal of the campaigns, and the ultimate success or failure of the campaigns.  Putting this data into a pivot table and a line graph, I will show how much these factors affected the success of their campaigns.  

## Purpose
##### To determine whether the initial goal and/or launch date of a fundraising campaign on Kickstarter is correlated to its success or failure. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
##### I created the pivot table shown below that includes how many campaigns failed, succeeded, or were canceled and then broke that data down by the months it happened in. What I found was that the number of plays that tend to be canceled is consistent from month to month.  The failed plays only seem to change based on how many total campaigns for funding there are in any given month. The only interesting conclusion that this pivot table does show us is that there is a much higher rate of campaigns successfully being funded starting in May and it slowly tapers off until around Aug where it goes back to almost exactly following the same line as the failed plays. This leads me to believe the best chance a campaign has for being funded is by starting it in May.


![alt text](https://github.com/GaryG484/Kickstart-Analysis-Mod-1/blob/main/Resources/Outcomes_vs_Goals.png)

### Analysis of Outcomes Based on Goals
##### Utilizing the line graph shown below, I charted what percentage of Kickstarter campaigns succeeded, failed, or were canceled based on their initial funding goal. The result is two perfectly symmetrically mirrored lines. What this suggests is that the funding goal is not an indicator of success or failure for a campaign. As the numbers go back and forth, I would suggest that there is another factor that is not included in this data that makes them so perfectly opposed. 


![alt text](https://github.com/GaryG484/Kickstart-Analysis-Mod-1/blob/main/Resources/Theater_Outcomes_vs_Launch.png)


### Challenges and Difficulties Encountered
##### The raw data I had to work with on the Kickstarter campaigns included information on 4115 different dramatizations with 14 facts for each play, film, and televisions series. That is a total of 57,610 data points that I started out with. The first challenge I was presented was cleaning this data so that only the data points that are relevant to my project are being utilized when I started analyzing the information. By creating more columns and breaking down the data I needed I turned those 57,510 data points into 86,415. This might seem detrimental but by separating the data into other columns I was able to use only the specific data I needed to make my conclusions on how correlated campaign success is to initial funding goals and its launch date. By separating the data and creating 86,415 data points, I was able to organize it and only take into consideration the much smaller sample set I was looking for. The main difficulty I ran into was figuring out how to organize the data into rows and columns so that I could take advantage of separating them. 

## Results

- There are two conclusions I can draw about the Outcomes based on Launch Date:
  - May is the best month to start a fundraising campaign on Kickstarter for a drama production. 
  - December through March appears to be the worst time to start a fundraising campaign on Kickstarter for a drama production. 

- A conclusion I can make from the Outcomes based on Goals is that the initial funding goal has little to no correlation to the ultimate success or failure of a productions Kickstarter campaign. 

- There are some limitations to this data set:
  - The data does not include a subcategory for what genre the productions are. A Halloween play looking for funding in March instead of October should not be compared to a play about 16th century London trying to get funding during the same time frame. One month seems like it would be much more relevant to one genre than the other.  
  - The time frame that each campaign was looking for funding is drastically different. A play that is looking for funding over the course of five months has a higher chance of reaching its goal than one that is only looking for funding over three weeks. 
  - Kickstarter is an online resource that is more commonly utilized by younger generations than older ones.  This can skew what time of the year donations are made as teenagers have more money in the summer and if they fail or succeed. 

- One graph that I could have chosen to display this data is a pie chart. This would have enabled me to present the percentage failed by months in an easier to understand model. I could have also utilized a bar graph to display the Outcomes based on Launch Date data as this would have made it easier to see which months are higher and which are lower.  
