
# 'Making-Of' Document of the Visualizations 

[Click here to view the project](https://public.tableau.com/profile/prerana7302#!/vizhome/Chicago-SpeedViolation-Visualizations2/Dashboard)


Here I document the process followed while creating the visualizations.
The audience of the visualizations would be the Mayor of Chicago. 


## Data Cleaning and Processing
The original dataset is speed camera violations in Chicago where each record gives the number of violations captured by a particular camera on a given day. The zipcodes in the original dataset seemed wrong hence I used another the dataset that had information about Chicago City's various wards, zipcodes etc. The two datasets were merged using wards as the field on which the join was performed.

[Source](https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Ward-Offices/htai-wnw4)

![Join](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/4.1.png)

The zipcodes were later used to collate  demographic information about the locations like median age, total, male and femal population. The demographic information was downloaded from the US Census Bureau website. 

I also created a Violation Season field by creating different groups by using the month variable.

![Seasons](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/4.2.png)

## Visualization 1: Population vs Violation Trend

I wanted the first visualization to give a general picture to the audience. Hence, I decided to explore the amount of violations recorded across time. I also wanted to show amount of violations occurred across different months over the years. I thought it would be interesting to compare the violations over time with population. The axis was changed to 'dual axis' in order to show both line graphs overlapping. 

![Version 1](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz2.2.png)![Version 2](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz2.3.png)

The question was, do violations increase or decrease over time? One would assume that with an increase in population, the number of violations also increase. To check if this assumption was true, I added the trend line to the graph. 
![Version 3](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz2.4.png)

Finally to focus on the trend, I reduced the opacity of the plotted graph so that the trend line sticks out.
![Final](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz2.5.png)

**Future Enhancements:**

* It would be great to present some more demographic data for Chicago, in order to learn more about the population Information like economic factors, age, distribution of males over females could be used


## Visualization 2: Population vs Violation Across Seasons

In the data exploratory phase, I had created a pie-chart to showcase number of violations across seasons.
![Previous](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz1.1.png)

I wanted to explore and understand how the volume of violations change over the seasons. I further checked if the number of violations change drastically over seasons in different years as well. A bar chart seemed like a good idea then.

![Version 1](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz1.2.png)

As the comparison across years was not very clear in version 1. I decided to change the x-axis from years to seasons and add year information on the chart itself. This made the chart even more confusion and was counter intutive. 

![Version 2](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz1.3.png)

Then, I decided to include both year and season on the x-axis. This made the chart a little better but still was too much information to processes with the different coloured bars. 

![Version 3](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz1.4.png)

This is when I decided that a line chart will convey the information cleanly. The trends across seasons were very clearly visible.

![Version 4](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz1.5.png)

Finally to compare the seasonality in violations and population I added population as another parameter. The dotted lines over each graph further explained the trends. The direction of the dotted line clearly explains the trend in which the violations increase or decrease across seasons and also the distribution of population in each season.

![Final](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz1.6.png)

**Future Enhancements:**

* I would like to study data about accidents across seasons and compare that with violations
* Would also like to create a forecast

## Visualization 3: Trends in Violations During different days of the week

I wanted to check if there was an insight as to the day on which most violations are recorded. I checked this for all the values in the dataset. 

![Version 1](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz3.1.png)

It can be observed that most violations are recoded on Friday. 

Taking cue from visualizations created in the exploratory phase, I wanted to check whether the addresses with 10 most recorded violations and the addresses with 10 least recorded violations show a different trend. 

![Version 2](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz3.4.png)

Version 2 shows the recorded violations for the top 5 addresses. Although overall it can be seen that Friday is not the day most violations are recorded for the top 5 addresses, the actual pattern for each addresses is really not clear here. Hence I decided to convert the visualization into a line graph. When it was done, the pattern for each address was clear.


![Version 3](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz3.6.png)

A similar visual for bottom 5 addresses was plotted. It was seen that for the bottom 5 addresses, the day with most violations was Wednesday. 

![Version 4](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz3.7.png)

While creating the dashboard, all three visuals were placed next to each other so that the patterns are easy for the user to understand and interpret.

![Final](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz3.8.png)

**Future Enhancements:**

* Since the axis of all three visualizations is the same, I would want to make it more uniform. 
* There is a hughe difference in the number of violations in the three graphs, especially between bottom 5 when compared to top 5 and all addresses. I would like to work on the scale of the graphs as well.
