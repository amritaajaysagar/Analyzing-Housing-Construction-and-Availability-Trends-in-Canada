# Analyzing Housing Construction and Availability Trends in Canada
### Amrita Ajay Sagar , Anupama Chalil Velluva , and Sarab Nidhaan Singh 
### November 28, 2023

This project aims to examine the trends and patterns of housing construction and availability in Canada, using data from 2009 to 2022. The data is obtained from Statistics Canada, a reliable source of official statistics on various aspects of the country. The data allows us to explore the complex interplay between the supply and demand of housing units.

## Objectives

Investigate housing construction trends from 2009 to 2022.
Analyze housing availability patterns during the same period.
Identify correlations between housing construction rates and housing availability.
Explore regional variations in construction and availability trends.

## Hypotheses

Correlation Between Housing Construction Rates and Availability: We hypothesize that there is a significant correlation between housing construction rates and the availability of houses. An increase in the number of houses constructed per year will correspond to a higher availability of housing for residents.
Regional Variations in Construction and Availability Trends: We assume that different regions in Canada exhibit distinct patterns in housing construction and availability. These variations may be influenced by factors such as population dynamics, economic conditions, climate, and cultural differences.
Regional Focus

Our study concentrates on five regions: Canada, British Columbia, Alberta, Ontario, and Nova Scotia.

## Data Collection

The data is obtained from Statistics Canada, a reliable source for official data about Canada. The housing construction data set contains information on the number of houses under construction in different regions of Canada from 2016 to 2023. The housing availability data set contains information on the number of private dwellings occupied by usual residents, private dwellings occupied by non-usual residents, private dwellings unoccupied, and total private dwellings in different regions of Canada from 2016 to 2023.

## Methodology

Data Cleaning: We cleaned and prepared the data for analysis by examining the structure of the datasets, selecting essential columns, ensuring correct data types, and eliminating duplicates.
Data Transformation: We transformed the data into a wide format for improved visualization and split the housing availability data by regions for focused analysis.
Hypothesis Testing: We assessed the association between the number of houses constructed per year in Canada and the number of private dwellings occupied by usual residents using the Chi-Square test.
Linear Regression Models: We constructed linear regression models to examine trends in housing construction and availability over time and by region.  

## Results

Housing Construction Trends: The rate of construction is increasing, with more houses being constructed every year in all the provinces. However, there are ups and downs in Alberta and BC, and the variation of the rate over provinces is also evident, with Ontario showing the maximum and Nova Scotia the minimum.
Housing Availability Patterns: The number of private dwellings unoccupied is increasing in all provinces and in Canada as a whole from 2016 to 2022. However, in BC, it has come down slightly from 2021 to 2022.
Correlation Between Housing Construction Rates and Availability: The Chi-Square test results (p-value = 0.227) suggest no significant association between houses constructed per year and private dwellings occupied by usual residents. The Pearson’s Correlation Coefficient Test indicates a moderately positive correlation (r = 0.6813) but lacks significance (p-value = 0.09193).
Regional Variations in Construction and Availability Trends: The T-Test comparing housing availability in Canada and British Columbia reveals a significant difference (p-value = 1.106e-10), supporting our intuition.

## Conclusion

Our comprehensive analysis of housing construction and availability in Canada from 2009 to 2022 reveals intriguing trends and insights. Visualizations showcase an overall increasing trend in construction rates, while regional variations are evident. Hypothesis testing indicates a lack of significant association between construction rates anddwellings occupied by usual residents, emphasizing the complexity of housing dynamics. Linear regression highlights a strong relationship between construction and passing years, though the impact of unoccupied dwellings appears negligible. These findings collectively underscore the multifaceted nature of Canada's housing landscape.

## References

Canada Mortgage and Housing Corporation, housing under construction: https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3410013901    

Housing stock in unit by institutional sector, housing type, dwelling occupation, dwelling type, and tenure type: https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3610068801    

In Hypothesis testing - cor.test(): https://www.rdocumentation.org/packages/stats/versions/3.6.2/topics/cor.test
