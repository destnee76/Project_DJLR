<<<<<<< Updated upstream
# Project_DJLR
Project 1
=======
# Global Health Expenditure

## Analysis of the WHO’s Global Health Expenditure Database 2000-2020 (Dec. 2022 version)

### Summary: Analysis of the following questions:

* How does the population growth rate impact the percentage expenditure on healthcare?
* Do countries with a larger healthcare expenditure allocate more or less towards contraceptive management?
* Does the consumption expenditure impact the percentage of the GDP spent on healthcare?

### Installation

* import matplotlib
* import pandas
* import numpy
* import requests
* import scipy stats
* import pprint

### Credits

* [W.H.O. GHE CSV Download](https://apps.who.int/nha/database/Home/IndicatorsDownload/en) 
* [W.H.O Global Health Expenditure Database](https://apps.who.int/nha/database/Select/Indicators/en)
* [National Health Expenditures, 2020: Spending Accelerates Due to Spike in Federal Government Expenditures Related to the COVID-19 Pandemic](https://www.ama-assn.org/system/files/prp-annual-spending-2020.pdf)
* [National Health Spending in 2020 Increases due to Impact of COVID-19 Pandemic](https://www.cms.gov/newsroom/press-releases/national-health-spending-2020-increases-due-impact-covid-19-pandemic)
* [Public healthcare expenditure as a share of GDP, 2019-Data source: World Health Organization](https://ourworldindata.org/financing-healthcare)
* [The Healthcare Imperative: Lowering Costs and Improving Outcomes: Workshop Series Summary](https://www.ncbi.nlm.nih.gov/books/NBK53914/)
  

### Challenges

* Working as a group to analyze, clean, and find a focus.
* Missing data on the GHE CSV, creating challenges when trying to accurately find correlations.
* Miscalculation with YoY population growth – created messy visuals and was difficult to diagnose.
* Finding data mistakes late in the process

### Conclusion

* There is no correlation between population growth rates and health expenditure. Between 1% to 3% of the population growth rate is responsible for a large percentage of total health spending. The analysis finds that 4% of the population with the highest health expenditures accounted for nearly half of total health spending in the world.
* Countries with higher Health Expenditure percentages do not, on average, allocate more towards contraceptive management.
* There is a weak positive correlation between 'Consumption Expenditure per Capita' and 'Healthcare Expenditure by Percentage of GDP' 





We hypothesized that if there were a correlation, there would likely be a negative correlation between the two variables, meaning that as Consumption Expenditure Per Capita increased the Percentage of GDP that is spent on healthcare, potentially implying that as individuals in a country had greater capital to spend, their wellbeing, and thus the amount the nation would spend on treating illness would likely decrease. The data proves the opposite. With a statistically significant positive correlation, it appears that as each variable increases, the other increases. This begs the question of why? we could likely determine where each nation is spending their healthcare dollars. Given the positive correlation in the analysis we could hypothesize that countries with lower Consumption Expenditure Per Capita would likely be spending a greater percentage of their healthcare expenditure treating acute illnesses such as communicable diseases, malnutrition and injuries(which may be cheaper to treat), while countries with a higher Consumption Expenditure Per Capita would be spending more of their healthcare expenditure treating noncommunicable diseases, such as cancer and complications from chronic conditions, such as obesity, which could be cheaper to treat. Life expectancy could also play a role, as the longer an individual is alive, the more healthcare dollars will need to be spent on their wellbeing. With further analysis of the GHED, and potentially other WHO databases such as the “WHO Mortality Database” we could test this hypothesis and potentially gather more complex insights into this relationship.  
>>>>>>> Stashed changes
