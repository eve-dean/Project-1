# **Project-1**
Overview

The dataset we used was compiled by the Washington Post Fatal Force Dataset. It provides data about each police-involved killing in the United States in 2015 and includes: City and State of the incident, the race, gender, and age of the deceased, and whether they were armed or experiencing a mental-health crisis. We combined this dataset with data on poverty rate, population, education rate, mental illness rate, and race distribution by cities from the US Census. This notebook focuses specifically on the number of shootings per year and the relationship between mental illness and police kilings. 

Data Cleaning

Dataframes were merged on city and state, and subset to only 2015 to look at mental health and anything adjusted for population. We focused our attention on 2015 because the data used for income, education and race distribution was for 2015 so focusing on a single year allowed us to merge data frames. When looking at 2015 relative to other years, it had an average number of shootings. Interestingly, 2021 had the highest number of shootings per year, but the largest YoY gap represents fewer than 100 shootings. All the data was either adjusted by population, per 1MM people, or compared to state averages in the general population. Most data was either groupd by city, state, 

Exploration

In our merged dataset we looked at the individual and combined demographic factors of age, race, and gender to see which groups are disproportionatley being killed by the police. We looked into additional factors of poverty, income, education, location, and mental illness to see if there were any other factors that affect the chance of being killed by the police. This notebook specifically looks at how the number of shootings changes over time and the relationship between mental health and police shootings. 

Conclusion

The demographic the most likely to be fatally shot by the police is a black male between the ages of 20 - 24, with approximately 304 incidents per 1 million. This demographic demonstrates that race, gender, and age play a major role in whether someone is fatally shot by the police or not. Mental illness was also determined to be another factor that impacts whether someone is fatally shot by the police, with the occurrence of mental illness among shooting victims as high as 40% in some states. When looking into median income, education, and poverty rate, the results were inconclusive. Overall the factors race, gender, age, and mental illness have a significant impact, while we could not determine a correlation with median income, education, and poverty rate. 
