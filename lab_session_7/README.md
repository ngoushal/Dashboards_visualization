
## Redesign of Lab-3

## Introduction -
The problem states to fetch the ticker symbols for the companies in the dataset that we have. Use the fuzzywuzzy logic and pandas reader to obtain the data in the desired manner. Join the two datasets on the Entity names so that it gives a picture of the stock prices and the records lost for each entity in the given year. Finally, develop a dashboard with a claim that supports/refutes the following claim
“The financial markets do not punish security breaches.”

## Objective-
The objective of this lab is to redeign the dashboard developed in lab-3 and document the scope of improvement.

## Data Source:
https://docs.google.com/spreadsheets/d/1Je-YUdnhjQJO_13r8iTeRxpU2pBKuV6RVRHoYCgiMfg/edit#gid=322165570

## Claim-
The financial markets do not punish security breaches.

## Warrant-
The stock price of a company reflect its financial state in the global market. 

## Qualification-
Data for 252 companies

## Critique on Lab-3
In the above chart, I have picked up one of the web companies (YAHOO) that had a huge data breach and then analysed its stock price over those years.

![Alt text](https://github.com/ngoushal/Dashboards_visualization/blob/master/lab_session_7/security_breaches.png)

Disadvantages Dashboards_visualization-
- Hides the ups and downs in the stock price that might have happened at the moment of data breach.
- It does not reflect how much was it affected and how long did it take to recover.
- If we analyse the data on a monthly basis, we would get a clear picture of the impact on stock prices.

Tableau link - https://public.tableau.com/profile/neha.goushal#!/vizhome/Final_251/FinalDB?publish=yes

### Scope of improvement-
- I can try to show a relationship in the number of records lost with the decrease in the stock price.
- I can try to show the rate change of security breaches over the years to identify a trend whether its increasing or decreasing 
- I can check each entity individually to see if there is a drop in price every time a security breach takes place.
- I can check if there is a pattern in particular type of organisations like tech or non-tech. Which ones are affected more? 
- I can analyse how long does the impact stay on the stock price for various entities. If we can identify a trend for this, it can be predicted that for a particular amount of security breach in a particular entity how long could it possibly take for an entity to cover up based on its historical experience.

## Conclusion-
The security breaches might have an effect at the moment of the breach but when we look at the bigger picture, there is no reflection on the stock price.

## References-
http://www.informationisbeautiful.net/visualizations/worlds-biggest-data-breaches-hacks/
http://d.yimg.com/autoc.finance.yahoo.com/autoc?query=%7B%7D&region=1&lang=en
https://github.com/seatgeek/fuzzywuzzy
https://pandas-datareader.readthedocs.io/en/latest/

