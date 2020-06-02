# UK-Pro-Cyclical-Mortality
## Investigating Pro-Cyclical Mortality in the UK during the 1991 and 2008 financial crisis

*All plots and data are availble in this repository.* 

Pro-Cyclical Mortality rates (a higher death rate during economic booms and a lower mortality rate during economic recessions) is a generally accepted fact. It is however not fully understood and seems initially counter-intuitive, since there are strong correlations between GDP growth and falling death rates, thus a dip in GDP would be expected to accompany an increase in mortality. Downturns also typically cause spikes in suicides and poverty levels, which would contribute to an increased mortality rate. 

In this notebook, we use UK deaths and population data between 1988 and 2018 to investigate this effect during the 1991 and 2008 financial crises, in particular to understand the impacts on different age groups.

### Project Aims

  * Plot mortality rates of different **age groups** for men and women between 1988 and 2018 to identify drops or spikes in mortality rates that may be associated with the 1991 and 2008 financial crises, and may provide insights into pro-cyclical mortality. 
  * Track mortality rates for **groups of people** born in different decades (e.g. compare people born in 1978 - 1988 with people born in 1988 - 1998) to see how the financial crises impacted the mortality curves of each group as they age. 

### Data

The data was sourced from the UK government website, the links are availabe in the notebook. We used 2 main sources of data: 
  * Population data that provides estimates of mid-year populations for each age group from 0 to 89 each year
  * Deaths data that provides the total deaths registered on death certificates for each age group from 0 to 89 each year 

The population data had some missing values that we estimated and had no data for the years 2016 - 2018. We sourced this data from another file and added it. The updated data including the estimated population data and extra years is available in this repository. Further details on the data cleaning and preperation are provided in the notebook. 




