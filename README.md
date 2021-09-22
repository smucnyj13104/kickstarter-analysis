# Kickstarting with Excel

## Overview of Project

### Purpose

- The purpose of this analysis was to determine how many theater or theater/play campaigns were successful, failed, or canceled based on their launch date (month) or funding goals. 

## Analysis and Challenges
 
- To determine how many theater campaigns were successful based on their launch date, a pivot table was created in excel (see TheaterOutcomesvsLaunchScreenshot.png). The pivot table was filtered by theater and used row labels sorted by month. The columns of the table were counts of the successful, failed, and canceled outcomes.
- To determine how many plays were successful based on their funding goals, the countifs excel function was used to count the number of successful, failed, and canceled outcomes after:
	1. including only plays
	2. counting the number of successful, failed, or canceled outcomes within a range of goals. 
	- A screenshot of this analysis can be seen in OutcomesvsGoalsScreenshot.png
- The challenges of this project were to figure out how to create row labels sorted by month for the first analysis and to figure out how to correctly enter the correct syntax into the countifs function. I determined how to create row labels sorted by month using a google search, and how to enter correct syntax by trial and error. The trial and error process involved comparing the output line chart to the output line chart displayed in the module. 

### Analysis of Outcomes Based on Launch Date

- Analyzing the outcomes based on launch date revealed that more successful outcomes relative to other outcomes occurred when the launch date was in late spring/early summer, i.e., May, June and July. Futhermore, the number of successful outcomes declined quite steadily during the fall months until January.

### Analysis of Outcomes Based on Goals

- Analyzing the outcomes based on goals found that, percentage wise, the most successful outcomes occurred when the goal was either small (less than $5000) or rather high ($35000 to $45000).

### Challenges and Difficulties Encountered

- As stated above, the challenges of this project were to figure out how to create row labels sorted by month for the first analysis and to figure out how to correctly enter the correct syntax into the countifs function. I determined how to create row labels sorted by month using a google search, and how to enter correct syntax by trial and error. The trial and error process involved comparing the output line chart to the output line chart displayed in the module. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	1. More successful outcomes relative to other outcomes occurred when the launch date was in late spring/early summer, i.e., May, June and July.
	2. The number of successful outcomes declined quite steadily during the fall months until January.

- What can you conclude about the Outcomes based on Goals?
	- Percentage wise, the most successful outcomes occurred when the goal was either small (less than $5000) or rather high ($35000 to $45000).
	
- What are some limitations of this dataset?

	- Some limitations are that the dataset does not provide locations more precise than the country of origin, and the dataset only goes back to the year 2009.
	
- What are some other possible tables and/or graphs that we could create?

	- We could create a table or chart of outcomes based on parent category, or a table or chart of outcomes based on country.