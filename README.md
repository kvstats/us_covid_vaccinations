# COVID-19 Vaccination Rates in the US

This analysis relates to COVID-19 vaccination rates in the United States. We are interested in exploring factors that are associated with differences in vaccine coverage by US county.

## Data Description
The latest data on vaccination coverage (and the data dictionary) can be downloaded here: https://data.cdc.gov/Vaccinations/COVID-19-Vaccinations-in-the-United-States-County/8xkx-amqh/data. 

## Analysis
We would like to build a regression model at the county level to help investigate patterns in the full vaccination rate for the population aged 18+ (that is, people aged 18+ who have received at least two vaccines). 

For this analysis, we considered modeling the outcome measure as a proportion of the population aged 18+ who are fully vaccinated by county using a binomial model, where $n$ is equal to the total population count in the county, $y$ is the number of people 18+ who are fully vaccinated, and $p$ is the proportion of the population aged 18+ who are fully vaccinated by county. 
