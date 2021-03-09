# Kickstarter Campaign Analysis

## Overview of Project

### Purpose: 
To assess Kickstarter campaigns, and divine information for a successful launch of a Theatre/Play.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date:
One of the first things to do was to convert the “Launch Date” into the standard mm/dd/yyyy format. 
Next was to organize the date into an easy to read table. A Pivot Chart was created using Outcomes and Launch Date. 
This allows the user to observe success/fail count quickly and efficiently by month. A line graph was generated to aid in the visual acuity of the data. 

### Analysis of Outcomes Based on Goals:
After analyzing outcomes based on launch date, the focus was shifted to determine “Outcomes based on goals”. 
An additional pivot chart was created to demonstrate these values. A second line graph was also made, to illustrated the success rates vs goal amounts. 

### Challenges and Difficulties Encountered:
No significant challenges were encountered during the analysis, but a couple of things to note that could potential occur are as follows…
- When looking at the “Outcomes vs Goals” graph you will observe a spike in successful campaigns for goals between 40,000 and 45,000. 
This should be considered an outlier as the number of campaigns with goal amounts that high are significantly less and garner a much higher fail/pass rate than 		the graph depicts. 
	
- As Louise was more interested in the outcomes of theater campaigns in Great Britain, the graphs do not accurately depict the success/failures for that criteria 		specifically but as a general outcome for all theater campaigns.  

## Results:
- What are two conclusions you can draw about the Outcomes based on Launch Date?
	Based on accumulated data, Kickstarter campaigns are favored for success if they are launched in late spring to mid-summer (May – July).
	The earlier at the beginning of the calendar year a theater campaign is launched the more likely they are to successful. 
	See “Theater Outcomes vs Launch Date” graph for visual aid.
	
	![](https://github.com/Apollo619/Kickstarter_Analysis/blob/main/Resources/Outcomes_vs_Goals.png)

- What can you conclude about the Outcomes based on Goals?
	Analysis revealed that Kickstarter campaigns with goals for less than 5,000 yielded a high percent of success than those of high amounts. 
	See “Outcomes vs Goals” graph for visual aid. 
	![](https://github.com/Apollo619/Kickstarter_Analysis/blob/main/Resources/Theater%20Outcomes%20vs%20Launch%20Date.png)
		
- What are some limitations of this dataset?
	We needed to create a column to indicate the duration from Launch date to the date the Goal was meet. 
	This crossed checked with successful campaigns can help identify the expected time frame for success to take. 
	The “Goal” column denotes dollar amounts, but we are working under the assumption that it’s US Dollar for everything even though the location of some plays is in Great Britain. 
	If there is a currency exchange for Goals, it might affect the graph for Outcomes based on Goals. 

- What are some other possible tables and/or graphs that we could create?
	As previously stated above, a new table with duration of launch date vs the date the goal was meet, this might provide more insight for when Louise should launch the 		campaign and how long she can expect to meet her goal.
 
