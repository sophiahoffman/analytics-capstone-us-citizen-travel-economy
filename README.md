# A Study of International Air Travel by US Citizens Based on Changing Domestic Economic Situations (1996-2019)

## Executive Summary
This analysis seeks compares international air travel statistics of US Citizens covering the years 1996 through 2019 and compares it to economic statistics such as unemployment, inflation and Adjusted Gross Income to see what factors most effect the travel numbers. Annual numbers are also compared on a year over year basis to determine which regions show the greatest growth and volatility with additional online research to answer why.

## Motivation
In light of the recent shutdown in travel due to Covid-19, the question came to mind of how, in general, the state of the US economic events impact the travel habits of US citizens. In the last 30 years, we have seen multiple, well defined cycles of recession and financial distress and recoveries, allowing an opportunity to perhaps see some trends.  

## Data Question(s)
1. How much is international travel affected by the economy?  
2. Do certain destinations become more popular when the economy is in distress?  
3. Do certain destinations become less popular?  
4. Do US citizens change where they travel to based on a change in the strength of the dollar?  

## General Observations:
Travel is a seasonal business with large fluctuations dependent on what might be considered peak vacation periods - summer vacation months of May through August and shorter periods for winter and spring break in December and March (generally).  

### A time series decomposition to break out seasonality shows the underlying trend in a monthly model  
![Seasonal decomposition](./workbooks/time_series_decomp.jpg)

The underlying trend shows a clear picture of increasing travel.  

Due to the noticeable seasonality of the business as well as statistics such as unemployment, analyzing trends from contiguous month to month is not effective. The majority of the analysis is done on an annual basis.  

## Data Question(s) Answered
1. How much is international travel affected by the economy?  
International travel is heavily affected by economic conditions with unemployment rate seeming to have the greatest impact. Factors such as inflation and exchange rate do not seem to have as much of a direct impact though they may be co-indicators of economic instability. But, the most visible impact is from catastrophic politically destabilizing events such as the 9/11 attacks. Travel showed an immediate decline with the tightening of restrictions and concerns over international traveler safety.  

2. Do certain destinations become more popular when the economy is in distress?  
Though I theorized that perhaps travelers might choose to stay closer to home, in this case, Canada and Mexico, during times of economic downturn, I did not see dramatic jumps in numbers. However, though travel to further destinations including the golden child of Europe continued to decline in 2010 and 2011, numbers traveling to Canada and Mexico did show an increase, which may indicate that they did see an earlier recovery or possibly shift in travel to closer destinations due to economic conditions.  

3. Do certain destinations become less popular?  
Overall and across the board, when economic and geopolitical conditions are unfavorable, travel declines. But travel to specific destinations may be heavily influenced by the cost of airfare. In fact, I theorize that competitive airfare and travel costs may be an even greater factor in determining what destinations are favored by US travelers. I was unable to find reliable, free data on historical airfare covering such a long period but it would definitely be worthwhile to see the impact it has on travel to specific regions. Also, having access to more granular data regarding destinations and travel demographics (aside from sampling poll results from the National Travel and Tourism Office) could lead to enhanced analysis.  

4. Do US citizens change where they travel to based on a change in the strength of the dollar?  
My assessment based on analysis is that exchange rates do not have a strong noticeable effect. In fact, it was rather uninspiring so it didn't make it into the visualizations.

Answers to Questions Not Asked:  
According to a 2017 analysis conducted and published by VISA, higher income individuals travel more - the propensity to travel was more strongly tied to higher (>$150K) income than age, even. Sure enough, plotting the number of individuals filing tax returns with Adjusted Gross Income of $100K or greater followed a similar pattern of increase as the line reflecting number of US citizen air travelers. This may have some significance or may be showing a correlation between state of the economy and increasing number of higher income returns.  

The Middle East and Africa has shown remarkable growth since 1996. The reasons related to this growth have not been specifically identified but certainly the modern architectural playground of the rich that describes Dubai has been an attraction. More research into what types of vacation packages and the affordability to travel to the region may play into this increase. Of course, starting from relatively small numbers of less than 200,000 travelers to the African region in 1996 and less than 500,000 travelers to the Middle East make it easier for relatively small increases to reflect as large ones in terms of percentage growth.

## Conclusion
Travel is heavily effected by geopolitical and economic conditions both domestically and internationally. Though factors such as inflation and exchange rates (which, despite volatility in specfic countries remain for the most part relatively stable or reflect an overall market condition) do not seem to have noticeable impact on travel, events or conditions that lead to high unemployment or lower income do tend to have a strong impact on US citizen international air travel. Recovery times vary by region but the underlying trend is that of increasing travel. Further research into historical air prices may yield interesting data as to how competitive a specific destination may be when cost of travel is considered.

## Data sources
Traveler information from National Travel and Tourism Office (https://travel.trade.gov/)
Economic statistics from St. Louis Federal Reserve Bank (https://fred.stlouisfed.org/)
Tax return data from Internal Revenue Service (https://www.irs.gov/statistics/soi-tax-stats-individual-income-tax-return-form-1040-statistics)

## Thank you ... 
To Mary and Mahesh for your dedication to quality instruction, support, insight and recommendations throughout this learning experience;
To Richard Champley at the National Travel and Tourism Office for additional support;
To Nashville Software School for providing exceptional quality educational programs.

