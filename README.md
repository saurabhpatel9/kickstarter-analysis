# kickstarter-analysis with Excel
	
## Overview of Project

	This project is a visual analysis of the outcomes of different fundraising campaigns based on two factors involved:
		1. launch dates
		2. funding goals

### Purpose

The purpose of this project is to compare the outcomes based on goals and the outcomes based on launch dates of the given funding campaigns. The analysis is carried out especially to determine the comparison between different categories/sub-categories, to depict how well Louise's play "Fever" did comparatively.
	
## Analysis and Challenges

### Analysis

The project mainly consists of analysis which depicts outcomes such as successful, failed and cancelled campaigns based on their categories/sub-categories on a monthly scale.
The parent category chosen for the analysis based on launch dates is "Theatre", which had shown a remarkable hike in the month of may, with a total of 153 campaigns faired constituting 111 successful outcomes.

The second analysis is based on the goals set, which clearly depicts a 75.81% of success rate for goals less than 1000, where as the goals ranging from 45000-49999, show the least amount of projects which is 1 with unsucessful outcome of 0%. The goals ranging from 1000-4999 consists of 534 which is the maximum number of campaigns with 72.66% of success rate, which consituted the highest proportion amongst the rest proving to be an optimal range.

### Challenges

The first challenge encountered during the first step of data cleaning and structuring, was the conversion of the launch dates from Unix format to a readable Date version. This challenge was overcome by the video sources found on google & youtube. The cell value was manipulated by applying the formula "=(cell_value)/86400+25569".

The second challenge encountered was the division of the category/sub-category from a single cell into two columns extracting the parent category and its sub-category to utilize it for analyzing based on launch date and goal. This challenge was overcome by going through the toolbar on top and searching for the filter option which brought me to the "Data" tab, which had the function "Text to Column" which solved the purpose.

![dates](https://user-images.githubusercontent.com/86158802/123897189-f19a2200-d930-11eb-9389-fdf98f5d5b1f.PNG)


### Analysis of Outcomes Based on Launch Date
![pivot_launch_date](https://user-images.githubusercontent.com/86158802/123897107-ddeebb80-d930-11eb-9755-7c078fbae898.PNG)

The pivot table depicts the outcomes of the Theatre as the parent category, which shows the peak for the campaigns launched in the month of May, which is then followed by a gradual dip, marking the month of December as the launch month with the lowest number of successful outcomes. The number of the most failed outcomes falls in between August and October. The cancellation rate had been periodical depicting a flat curve with an exception of no cancellations during the month of October.

### Analysis of Outcomes Based on Goals

![goals_chart](https://user-images.githubusercontent.com/86158802/123897232-0971a600-d931-11eb-98eb-52dd3e349c68.PNG)

The Events with lower financial goals are seen to be more successful compared to the events with higher financial targets. All the events in the "Play" category, depict 0% cancellation rate. The Analysis also depicts that approximately 92% of the events have a financial target below $15000, making it one of the most favourable financial goals.

### Challenges and Difficulties Encountered

Most of the campaigns with higher goal range has failed, however, the sample size of the higher range is not big enough to be comparable with the lower goal range events, which served as a limitation.
The second difficulty faced was the division of the category/sub-category from a single cell into two columns extracting the parent category and its sub-category to utilize it for analyzing based on launch date and goal.

## Results

<b>- What are two conclusions you can draw about the Outcomes based on Launch Date?</b>

The analysis suggest that summer season months, mainly May can be marked as a favourable month for launch for successful outcomes, and the month of December marking the least successful outcomes, making it the most unfavourable month for the campaign launch.

Overall success of the events stands at 61%. In addition to this, events in the month of december deviate the most(-12%) from the overall average success of the events 
	
<b>- What can you conclude about the Outcomes based on Goals?</b>

Three quarter of events having goal below $5000 have been successfull. The events with lower targets are poised to be more successfull compared to the events with the greater financial targets

<b>- What are some limitations of this dataset?</b>
since there are very few events which have higher targets , to compare them with the events with the lower targets is not possible as the sample size is not big enough for it.
since different events have taken place in different countries, to be able to compare the success of the events,the currencies need to be normalized to one standard currency most popularly USD

<b>- What are some other possible tables and/or graphs that we could create?</b>
Other possible graphs and calculations which can be used for the analysis include: 
1: Frequency of event types over the years(to compare which events occured most frequently in a particular year)
2: Count of successfull events ,failed events and cancelled events by country (Bar Chart)
3: Percentage of events by country whose pledge exceeded the goal.
4: Top events with highest pledge to backers ratio to highlight which events took least number of backers and gained the most.

