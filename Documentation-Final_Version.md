
# City of Chicago - Speed Violations - Documentation  

[Click here to view the Final project](https://public.tableau.com/profile/prerana7302#!/vizhome/Chicago-SpeedViolation-Visualizations2/Dashboard)

## Dataset 
The records for the current year, 2019 were filtered out from the dataset. 

## Visualization 1: Trends in Population and Violations

The aim of this visualization was to show a trend to the Mayor and explain the behavior of the population in general. The comparison was made between population of the city with the number of violations across from 2014 to 2018. Records for each month of the years were plotted. This led to an interesting finding that though the population of the city showed an increasing trend the number of violations captured were going down. 

I then decided to include trend lines in the visualization. After checking the trend line data, it can be seen that the p-value is below 0.0001 which show high significance. The trend line for population is 0.11 which means no significance. Despite this, the findings still hold true. 

To add a level of interactivity to the visualization, the filter with Year was added. This allows the user check population and violation trends for a particular year or a group of years. 

![Viz 1](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Ver2-1.png)

## Visualization 2: Average violations vs number of cameras

The second visualization, while it presented the number of violations across different seasons in comparison with the population trend in those seasons, it really didn't convey much meaning to the audience. Hence, I thought it would give more value to the audience if average violations were compared against the number of cameras in that season. When I plotted the average violations across the four seasons, it was clear that Spring, Fall and Winter followed a similar trend while Summer was completely different. 

Also, while trying to understand more about the Speed Violations program, I had read that cameras near schools were de-activated on weekends and for most of the summer, while the cameras near parks were active for all seven days of the week. [Chicago Speed Enforcement Program](https://www.chicago.gov/city/en/depts/cdot/supp_info/children_s_safetyzoneporgramautomaticspeedenforcement.html) Hence, I decided to plot the number of cameras across Summer and other seasons combined. 

The finding was that the average speed violations for all years was much higher in Summer when compared to other seasons. This was true in spite of the fact that the number of active cameras were significantly lower in Summer than in any other season across all years. This means that the significantly lesser number of cameras in Summer captured more violations in Summers than any other season. 

![Viz 2](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Ver2-2.png)


## Visualization 3: Trends in Violations based on addresses

Here the aim was to check if there were any outliers based on location in terms of the number of violations. To showcase how the violations changed based on locations, they were plotted against all addresses first and then for top five addresses with most violations and bottom five addresses with most violations.

The graphs themselves were not changed much from the last version. Cosmetic changes like changing the graph colours to show high or low violations in the all addresses graph, removing gridelines, adding annotations etc. were added to the visualization. This has helped make the visualization consistent and easy on the eye. 

Also to show all the three graphs together, a dashboard was created. 

What can be observed is that even though for all addresses the day with most violations seems to be friday, it is different for top five and bottom five addresses with most violations. This shows that the top five and the bottom five addresses behave differently than the average. 

For the top five addresses the day with most violations seems to be Saturday and for the bottom five addresses the day with most violations is Wednesday. This ties back to the finding in visualization 2. In fact, for the bottom five addresses the graphs show no values for saturday and sunday. This means that these are addresses where schools are located. And, the top five addresses are the ones which are close to parks.

![Viz 3](https://github.com/preranap1/Chicago-City-Speed-Camera-Violations-Visualizations/blob/master/Images/Ver2-3.png)


These three visualizations were then put together in the form of a story as opposed to a dashboard like the previous version. The advantage of the story format was that it was easier to explain and build in the story-telling aspect which is an essential pillar for building a good visualization framework.

