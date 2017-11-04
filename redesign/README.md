

## Project Statement:

United States has the highest number of obese people in the world. An adult who has a BMI between 25 and 29.9 is considered overweight. An adult who has a BMI of 30 or higher is considered obese. According to the most recent data, adult obesity rates now exceed 35 percent in five states, 30 percent in 25 states, and 25 percent in 46 states. West Virginia and Mississipi have the highest adult obesity rate with the highest number of diabetic patients and Colorado has the lowest obesity rate with least number of diabetic patients.
The adult obesity rate decreased in Kansas between 2015 and 2016, increased in Colorado, Minnesota, Washington, and West Virginia, and remained stable in the rest of states. This supports trends that have shown overall leveling off of obesity rates in recent years.

## Motivation:
When I was shortlisting, I went through a list of topics on the website makeovermonday and came through the topic of obesity. The United States has the highest percentage of obese people in the world and obesity has a crucial public health impact. The estimated direct and indirect costs of obesity and being overweight in the US are $117 billion and rising rapidly. This figure exceeds even the annual costs of tobacco-related illnesses. So I thought of taking up this topic and coming up with the visualization that makes people aware of the consequences of obesity so that they can take preventive measures.

## Intended audience:
Government health organiszations, healthcare professionals, and general public

## Objective:
To redesign and develop a claim for the existing data visualization on adult obesity in the United States.

## Critique on the original Visualization:
![Alt text](https://github.com/ngoushal/Dashboards_visualization/blob/master/redesign/Original1.png)

![Alt text](https://github.com/ngoushal/Dashboards_visualization/blob/master/redesign/Original2.png)

- Firstly, the map just shows the rate of obesity in various states and does not tell what can be done to prevent it.
- Secondly, It also shows the trend over the years in each state but there is no identified pattern in any of the states.
- The visualization does not consider the reasons why the obesity rate is high in few states as compared to the others.
- It does not even tell us the distribution of obesity by age groups or income levels or gender.
- This visualization is just a representation of the factual data leading to no conclusion or claim.

## Scope of improvement:
If the visualization had identified a pattern over the years, maybe a reason could have been identified that is leading to obesity and then the health institutions can take measures in that direction.
Also, if it compares based on gender or age group, it would be easy for the organizations to focus on particular target and develop dieting charts or activity plans based on the particular target.
Lastly, if there are particular regions facing this problem constantly every year, there can be special training camps and awareness campaigns organized for them to enlighten the people.

I have tried to compare the obesity rate based on gender, income and age group in various states. Also, I took the data of the number of diabetic people in the United states and compared that with the given data. It lead to the conclusion that obese people are more prone to Diabetes.


## Development process:


### Data wrangling steps:
The data was obtained from the links mentioned above under the data section. The data collected from the website had fields like State names, year, obese percentage and a category. The year values range from 2011-2015. It includes all the states in United States of America and also categorizes them based on gender, age and income. 
This data also had a few irrelevant columns like low confidence interval, high confidence interval, topic, survey question which have not been used in developing the visualization.
The data was clean and readable for Tableau and hence, there was not much data wrangling required for this case.

### Data sources:
- Various sources for visualization
http://www.makeovermonday.co.uk/data/ 
The website from where I found various topics for data visualization and selected the topic of adult Obesity in The United States

- Adult Obesity in US
https://stateofobesity.org/adult-obesity/
This is the link for obtaining the original data for the visualization. This visualization shows the values for the years 2009-2016 but the data source has values for the years 2011-2015.

- Diabetes in US
https://stateofobesity.org/diabetes/
This is the link that provides data for the number of diabetic people in United States by states for the years 2011-2015


### Visualization:

### - Claim:
Obesity increases the risk of diabetes

### - Qualifier:
Obesity in the United States of America

### - Warrant:
Obesity increases the blood sugar level leading to higher risk of diabetes

### - Backing:
These links provide information on the fact that obesity increases the blood sugar levels.
https://www.sciencedaily.com/releases/2009/06/090621143236.htm
http://www.obesityaction.org/educational-resources/brochures-and-guides/understanding-excess-weight-and-its-role-in-type-2-diabetes-brohure

### - Reservations:
The claim is formed only on the basis of obesity rate in US. If we consider the global data, it might show a different picture. 

## Intermediate versions:
### - Version1
![Alt text](https://github.com/ngoushal/Dashboards_visualization/blob/master/redesign/Version1.png)

This shows the change in average total obese rate over the years. This is calculated by finding the difference in current year value and previous year value. This helps us to know has there been an increase or decrease in the rate over the years and if yes, then by how much. 

The overall trend shows that obesity rate has been increasing over the years in United States. Even though its increasing overall, the amount by which it is increasing is reducing each year which means that people are taking precautions. 

Of all the years, the maximum increase (.7%) was in the year of 2013, when 38 states had an increasing obesity rate. 2015 had the least change in percent which was (.1%). This shows that people are becoming aware of the problem and improving their eating habits. Also, 23 states had a decreasing rate of obesity in 2015 as compared to 13 states in 2013.



### - Version2
![Alt text](https://github.com/ngoushal/Dashboards_visualization/blob/master/redesign/Version2.png)

This chart shows the obesity rate by gender. It gives a picture that males have a higher obesity rate as compared to females. Th difference is not significant but males are always above the females.


### - Version3
![Alt text](https://github.com/ngoushal/Dashboards_visualization/blob/master/redesign/Version3.png)

This graph shows that the people aged between 18-35 are less obese than the people of age 35 and above.
Also, it shows that the obesity rate in both the age groups is increasing significantly.

The number of obese older persons has markedly increased because of both an increase in the total number of older persons and in the percentage of the older population that is obese. An important determinant of body-fat mass is the relationship between energy intake and expenditure. The energy intake i smore compared to the expenditure at an older age. The amount of physical activity a person does reduces after an age.

### - Version4
![Alt text](https://github.com/ngoushal/Dashboards_visualization/blob/master/redesign/Version4.png)

This chart shows that obesity rates tended to increase with decreased income. It has been found that individuals who live in impoverished regions have poor access to fresh food. Poverty-dense areas are oftentimes called “food deserts,” implying diminished access to fresh food. The healthy food is not affordable for the low income category people. Since junk food is easily accessible and cheap, they tend to have more junk.

### - Version5
![Alt text](https://github.com/ngoushal/Dashboards_visualization/blob/master/redesign/Version5.png)

This chart shows that educated people are less obese.
This directly comes from the fact that educated people are more aware of the consequences of obesity and they keep a control on their dieting habits. They earn more from the people who are less educated and hence they have better access to healthy food. 

## Final visualization:
![Alt text](https://github.com/ngoushal/Dashboards_visualization/blob/master/redesign/Finalversion.png)

The map with orange shades shows the distribution of obesity rate in the United States over the years. It is the average of obesity rate for the years 2011-2015. The map with shades of blue shows the distribution of percentage of people with diabetes in the United States over the same period. 

The region where the obesity rate is high is the region which has the maximum number of diabetic people. The southern part of US is the most obese and most exposed to the risk of diabetes. As we move towards the western side, the obesity rate decreases and so does the diabetic rate.

This conludes that people with obesity are more prone to diabetes. 


## Actions/Corrective measures:
### Government health organizations:
- Government should focus on supporting healthy eating and active living.
- The government should motivate people to help improve the dietary quality
- The government should grant colleges and universities to work with cooperative extension and outreach services in states that have a higher obesity rate.
- The government should try to come up with schemes that can make healthier foods more accessible and affordable to everyone.

### Healthcare professionals:
- Doctors can have a string influence on the health choice of individuals.
- They can be the role models for healthy lifestyle.
- They can bring their knowledge and standing to advocate for healthy changes that reach people well beyond the walls of the clinic.
- They should create and promote prevention programs that can be instituted plan wide; and use their status in the community to support and sponsor wide-ranging prevention efforts, such as healthy meals in school, jogging and walking events, and the education of policymakers.

### General public:
- People should become more cautious towards what type of food they are consuming.
- They should try to improve their eating habits and increase physical activity.
- After the age of 35, they should find ways to be physically more active either by having a regular exercise schedule or figuring out alternative means to exercise.

## Road map with future enhancements:
- Over the years, the regions with maximum obesity are the same which shows that the government has not been taking any measures to reduce the numbers and to spread awareness  
- In the future, I can think of a campaign or a plan that can be organized in those regions to make people aware of the problem
- The rate of increasing obesity over the years can be related to the social activity of the people over the internet. During the 1990’s the obesity rate was much lower and with more people moving towards socialization over the internet, the physical activity and the body movement has reduced leading to higher rate of obesity


## References : 

http://adph.org/administration/obesityfactsheet.pdf
https://www.cdc.gov/brfss/brfssprevalence/
https://www.salon.com/2014/08/01/10_reasons_america_is_morbidly_obese_partner/
https://www.ruralhealthinfo.org/community-health/obesity/3/targeting-audiences
https://www.hsph.harvard.edu/obesity-prevention-source/obesity-prevention/healthcare/healthcare-obesity-prevention-recommendations-complete-list/


 

