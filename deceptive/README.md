# Number of deaths caused by air pollution

## Introduction:
Air pollution can be defined as the emission of harmful substances into the atmosphere. This visualization project presents a global-level overview of air pollution: trends from history to the present day, the health and mortality burden and risk from air pollution. Air pollution is of two types: indoor (e.g. household) contexts and outdoor environments. This dataset focuses on impacts of outdoor air pollution. 

## Motivation:
Air pollution is perceived as a modern-day curse: a by-product of increasing urbanisation and industrialisation. Air pollution has a range of negative impacts, including human health, damage to ecosystems, food crops and the built environment. The World Health Organisation highlights air pollution as the greatest environmental risk to human health. It estimates that 3 million people die because of outdoor pollution every year. Because of the huge impact on human health, i thought of going in-depth about this problem and figuring out the countries where it affects the most,its overall impact and its trend.

## Intended Audience:
- World health Organisation
- Government
- Environment concerned committees

## Objective:
The objective of this project is to create a data visualization that purposefully distorts the data or deceives the reader. The purpose of this project is for us to experience and realize the ethical implications of design decisions during the development of data visualizations.

## Development Process:

**Claim:**

Absolute number of deaths is increasing over the years

**Warrant:**

A ‘death’ from air pollution is defined as someone who dies prematurely (could be in the range of months or years) than would be expected in the absence of air pollution. In many cases, air pollution exacerbates pre-existing cardiorespiratory illnesses, for example, individuals suffering from asthma are particularly vulnerable. Researchers link pollution concentrations to health risks using empirical exposure-response relationships and their relation to mortality rates.

**Qualification:**

- This data is only for the period 1990 - 2010
- This dataset focuses on the number of deaths caused by outdoor air pollution.

**Reservation:**

If the data for indoor air pollution and other types of pollution is also considered, the claim might alter.

## First Version:
**"Absolute number of deaths is increasing over the years"**

Absolute number of deaths is the number of deaths that occurred in a specified geographic area during a given period of time. The below visualization shows that the absolute number of deaths is increasing over the years for the countries globally. I have plotted the graph with average number of deaths on the Y-axis and year on the X-axis. As you can see, the number was 18,548 in 1990 and has increased over the years and reached 21,098 in 2010. This is plotted by taking all the countries for the average.

Link to Tableau : https://public.tableau.com/profile/neha.goushal#!/vizhome/Deceptive_0/Dashboard1?publish=yes

![Alt text](https://github.com/ngoushal/Dashboards_visualization/blob/master/deceptive/ver-1.png)

### Deceptive visualization:

**Intermediate versions:**

The visualisation below shows the absolute number of deaths attributed to outdoor air pollution by country from 1990-2016. At the annual level, the pollution related deaths are dominated by China and India – each with between 1.1-1.2 million deaths in 2016. In the period since 1990, China’s increase in pollution related deaths appears to be slowing with only a small increase since 2010. In contrast, India’s mortality rate from outdoor air pollution continues to increase.

These are the two anomalies(India and China) in the dataset. Their huge population is affecting the overall number in the calculation. If these two countries are not considered, the graph shows a completely different trend of the number of deaths.

Link to Tableau : https://public.tableau.com/profile/neha.goushal#!/vizhome/Deceptive_0/Dashboard2?publish=yes

![Alt text](https://github.com/ngoushal/Dashboards_visualization/blob/master/deceptive/ver-2.png)

### Final version:
**"Absolute number of deaths remain constant over the years"**

Since the two countries, India and China have an unexpected behavior, I tried plotting a graph without including these two in the calculation for average. The below visualization shows the revised version of previous graph by excluding India and China. As a result, I realized that there is a huge difference in the values. As you can see, the value for the year 1990 drops down from 18,548 to 9,458.5 and the value for the year 2010 drops down from 21,098 to 9,952.3. This is a huge difference. Also, you can see that the graph line does not show any increasing trend over the years. Rather, the number reamins almost constant for other countries over the years. This proves that the first visulaization was deceptive and makes the audience believe that the number of deaths are increasing over the years whereas actually its not.

Link to Tableau : https://public.tableau.com/profile/neha.goushal#!/vizhome/Deceptive_0/Dashboard3?publish=yes

![Alt text](https://github.com/ngoushal/Dashboards_visualization/blob/master/deceptive/ver-3.png)

### Claim:
**"Death rate is decreasing over the years"**
Another way of improving the chart and showing an opposite opinion is by using a metric that is calculated from the absolute number of deaths.

Link to Tableau : https://public.tableau.com/profile/neha.goushal#!/vizhome/Deceptive_0/Dashboard4?publish=yes

![Alt text](https://github.com/ngoushal/Dashboards_visualization/blob/master/deceptive/ver-4.png)

You might be wondering that if the death rate across many countries is falling, why are the absolute number of deaths increasing? The absolute number of deaths is a function of three variable: the death rate, the population size, and the age demographic of the populace. If two countries have the same death rate, the country with the larger population, or older population will have the largest absolute number of deaths.

Hence, measuring the absolute number of deaths from air pollution is not a good metric for comparison among countries because it presents a number of drawbacks. The first is that the absolute number of deaths as a measure of air pollution does not take into account the population size or demographic. We might logically expect the number of deaths to be higher in countries with larger populations, and to increase in line with population growth. Similarly, we might expect the number of deaths to be higher in countries with an older population demographic.

Another drawback to the absolute number of deaths is that it provides no indication of the age of the individuals included in these statistics; for example, a child who dies from an illness related to air pollution is counted exactly the same as an older individual who died a few months earlier than expected. 

For many countries, the death rate has declined by more than 50 percent. This reduction trend is true, even in countries with a growing absolute number of deaths, for example-China and India. The increase in absolute number of deaths from air pollution is therefore a larger reflection of the changing population structures—a growing and aging population rather than an increased individual risk of mortality.

### How is death rate calculated?:
Death Rate is the total number of deaths in a specified geographic area (country, state, county, etc.) divided by the total population for the same geographic area for a specified time period, usually a calendar year and then multiplied by 100,000. 

Death rate has four components:
1. A specified measurement period.
2. The numerator, the number of deaths that occurred in a specified geographic area during a given period of time
3. The denominator, the total number of people in the population at risk in the same geographic area for the same period.
4. A constant. The result of the fraction is usually multiplied by some factor of 10 (100,000), so that the rate may be expressed as a whole number. 

**Calculation:**

Death Rate = (Absolute number of deaths/Total population)*100,000

### Data Sources:
https://ourworldindata.org/air-pollution/

## Conclusion:
If we look only at the number of absolute deaths, we are under the impression that the numbers for countries are increasing over the years. It is actually the anomalies or the wrong metrics that gives us this conception. The truth is that death rate is the comparable metric as it takes other factors into account and gives us the true picture of the actual trend.

Death rates are reported as age-standardized figures to allow for a fair cross-comparison of mortality and morbidity risk between countries and through time. Age-standardization normalises death rates to a set population structure (population, size and age) to cancel out variation which would occur between countries based on population demographics. If rates were not age-standardized, a country with a larger or older population would report higher death rates than a smaller or younger country, even if levels of pollution exposure were the same.

## Road map with future enhancements:
- We can analyse the trend for the period before 1990 and then compare the current data to see the overall change.
- We can analyse if the countries with more air pollution are actually the countires with higher death rate? or if its affected by other factors too?
- What can be the cause for countries with less air pollution but higher death rates?
- We can analyse other factors which improve overall health and vulnerability in the countries with lower number of deaths and then compare it wth the countries that have a higher number of deaths.
- This comparison can be made more effective by including the impact of age in mortality data and different age-distributions in different populations. Age-adjusted mortality rates can be used for comparative analysis. 


## References:
https://ourworldindata.org

https://www.stateofglobalair.org/data

http://www.healthdata.org/results/data-visualizations

https://ourworldindata.org/grapher/absolute-number-of-deaths-from-ambient-particulate-air-pollution



