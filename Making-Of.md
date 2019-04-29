
# 'Making-Of' Document of the Visualizations 

Here I document the process followed while creating the visualizations.
The audience of the visualizations would be the Mayor of Chicago. 


## Data Cleaning and Processing
The original dataset is speed camera violations in Chicago where each record gives the number of violations captured by a particular camera on a given day. The zipcodes in the original dataset seemed wrong hence the dataset was merged with another dataset using wards as the field on which the join was performed. The zipcodes were later used to collate  demographic information about the locations like median age, total, male and femal population. The demographic information was downloaded from the US Census Bureau website. 

## Visualization 1: Population vs Violation Trend

I wanted the first visualization to give a general picture to the audience. Hence, I decided to explore the amount of violations recorded across time. 

![Version 1](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz2.1.png)


I also wanted to show amount of violations occurred across different months over the years. I thought it would be interesting to compare the violations over time with population. The axis was changed to 'dual axis' in order to show both line graphs overlapping. 

![Version 2](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz2.2.png)![Version 3](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz2.3.png)

The question was, do violations increase or decrease over time? One would assume that with an increase in population, the number of violations also increase. To check if this assumption was true, I added the trend line to the graph. 
![Version 4](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz2.4.png)

Finally to focus on the trend, I reduced the opacity of the plotted graph so that the trend line sticks out.
![Version 5](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Viz2.5.png)



**Future Enhancements:**

* It would be great to present some more demographic data for Chicago, in order to learn more about the population. Information like economic factors, age, distribution of males over females could be used.
* Another enhancement would be to include forecast.



