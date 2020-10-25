# Baltimore City


## Background

[CBS Baltimore](https://baltimore.cbslocal.com/2017/07/06/life-expectancy-baltimore/) stated there are discrepancies in terms of life-expectancy in different areas of Baltimore. In fact, poorer areas of Baltimore had a life expectancy that was 20-years lower than that of richer areas. Lower life expectancy and higher rates of mortality in poorer areas indicate that people are dying prematurely when these are preventable solutions, as those in richer areas are not dying so early. This problem is important as obviously we would like to create for a more equitable society, where people's livelihoods are not affected based on where they live- especially if there are ways to do so. 

According to [Baltimore City’s health department](https://health.baltimorecity.gov/state-health-baltimore-winter-2016/state-health-baltimore-white-paper-2017#:~:text=The%20leading%20causes%20of%20death,and%20chronic%20lower%20respiratory%20diseases), the leading cause of death in the city is heart disease. Life expectancy and mortality rates in the 44-64 age group in Baltimore can be assumed to be correlated with heart disease. 

There are many different causes of heart disease, but [The Mayo Clinic](https://www.mayoclinic.org/diseases-conditions/heart-disease/symptoms-causes/syc-20353118) states that the most common type of heart disease, atherosclerosis, is caused by an unhealthy diet, lack of exercise, and being overweight. These are issues that are amendable. Thus, working with food system initiatives is a practical way to help. Hence, a look into various variables related to food systems in neighborhoods in the city of Baltimore was endeavored.

This is of interest to us because we are both Baltimore citizens at least until we graduate from Hopkins. We both come from areas that are economically better than Baltimore, so perhaps we could implement aspects that we have seen in our own hometowns to improve food safety in Baltimore. Furthermore, this is relevant for government officials who could learn the most effective ways to increase life expectancy and decrease rates of mortality by route of food safety. Not to mention, the leading cause of death in the United States is heart disease, so information from our analysis could help with the larger United States as well. It shouldn't be the case that you can live longer if you live in a more well-off neighborhood.

- need to explain what the different variables mean !! !


## Business Question

___How can we combat life expectancy and mortality rates in the 44-64 age group in Baltimore City through food system initiatives?___


## Open Data 

__[Baltimore Neighborhood Indicators Alliance](https://vital-signs-bniajfi.hub.arcgis.com/):__ 

ADD LINKS!!!!


## Data Questions

_How does the data group itself into separate clusters of neighborhoods in Baltimore City?_

## Data Analysis 

__Regression__

We initially wanted to look and see whether all our variables were significant enough to affect the dependent variable. However, after doing multiple linear regression analysis for both mortality rate and life expectancy, only 1-2 variables were significant, so we decided to do simple linear regression on 2 variables, free and reduced meals and median household income.

(graph for mortality rate)

__**Mortality Rate, 44-64:**__

The p-value for free and reduced meals was 7.5133E-11 and the p-value for median household income was 2.5459E-11, meaning that both these independent variables were significant and are able to explain the changes in the dependent variable. As we can see in the graphs above, the trendline mostly fits the shape and direction of the data points and there are no extreme outliers that skew the data. Mortality rate has a positive relationship with free and reduced meals and has a negative relationship with median household income. This means that mortality rate increases when there are more free and reduced meals and mortality rate decreases when median household income is greater.

Equations:

Mortality rate = 1.922(free/reduced meals) – 21.416

Mortality rate = -0.001(median household income) + 180.110

(graph for life expectancy)

__**Life Expectancy:**__

The p-value for free and reduced meals was 8.0678E-11 and the p-value for median household income was 6.3693E-14, meaning that both these independent variables were significant and are able to explain the changes in the dependent variable. As we can see in the graphs above, the trendline mostly fits the shape and direction of the data points and there are no extreme outliers that skew the data. Life expectancy has a negative relationship with free and reduced meals and has a positive relationship with median household income. This means that life expectancy decreases when there are more free and reduced meals and life expectancy increases when median household income is greater

Equations:

Life expectancy = -0.240(free/reduced meals) + 90.609

Life expectancy = 0.0001(median household income) – 66.240




__Clusters and Their Characteristics__

![alt text](https://gith) <- Maybe add chart????

_Mortality Rate:_ 

_Cluster 1_: Cluster in between Cluster 2 and 3 in terms of all measures.

_Cluster 2_: Lowest free and reduced meals and lowest average health index. Highest median household income, number of bike lanes. Most below level of mortality rate. 

_Cluster 3_: Highest above average number of people in free and reduced meals. Also, the lowest median household income, number of bike lanes, and average health index among the different clusters. Highest above average rate of mortality. 


_Life Expectancy:_ 

_Cluster 1_: Cluster in between Cluster 2 and 3 in terms of all measures.

_Cluster 2_: Least well-off. Highest above average number of people in free and reduced meals. Also, the lowest median household income, number of bike lanes, average health index, and life expectancy among the different clusters.

_Cluster 3_: Most well-off. Lowest free and reduced meals and lowest average health index. Highest median household income, number of bike lanes, and life expectancy. 

The cluster analysis helps us understand where to focus our efforts and initiatives. We should focus on the neighborhoods in cluster 2 for both analyses. 


__List of Baltimore Neighborhoods in Cluster 2 maybe???__
__Maybe add the graphic__


## Business Answer and Further Suggestions
