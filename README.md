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
* [WHY POPULATION MATTERS](https://populationmatters.org/the-issue/#:~:text=We%20have%20to%20address%20overpopulation&text=More%20people%20require%20more%20food,plastic%20and%20forests%20are%20disappearing.)
  

### Challenges

* Working as a group to analyze, clean, and find a focus.
* Missing data on the GHE CSV, creating challenges when trying to accurately find correlations.
* Miscalculation with YoY population growth – created messy visuals and was difficult to diagnose.
* Finding data mistakes late in the process

### Conclusion

* There is no correlation between population growth rates and health expenditure. Between 1% to 3% of the population growth rate is responsible for a large percentage of total health spending. The analysis finds that 4% of the population with the highest health expenditures accounted for nearly half of total health spending in the world.
* Countries with higher Health Expenditure percentages do not, on average, allocate more towards contraceptive management.
* There is a weak positive correlation between 'Consumption Expenditure per Capita' and 'Healthcare Expenditure by Percentage of GDP'

