# Nigeria-COVID-19-Data-Analysis-Using-Python
Data Scientist Microdegree Capstone Project

## Project Overview
Coronavirus disease (COVID-19) is an infectious disease caused by a newly discovered coronavirus, and it has affected major parts of the world. Nigeria, a West-African country, has also been affected by the COVID-19 pandemic after recording its first case on 27th February 2020.

Nigeria is a country with 37 states - Federal Capital Territory included- and a fast-growing economic environment with about 200 million citizens. COVID-19 has affected several country activities as the country steadily progressed from its first case to shutting down major airports, state-wide lockdown, curfews, and reviving its economy.

In this project, I employ data science & analytics skills to collect data, explore the data, perform analysis, create visualizations, and generate insights.

## Steps/Approaches

### Step 1
This step involves gathering data needed for the analysis from different sources, some of which are from websites, github repos, or external files.

1. Performed a web scrap to obtain data from the NCDC website. Utilized the BeautifulSoup library to achieve this.
2. Imported data from the John Hopkins github repository.
3. Imported the provided external data into jupyter notebook.

### Step 2
Viewed and obtained basic information like `head()` and `info()` about the imported data from the previous step.

### Step 3
Here I clean and manipulate the collected data to ensure it is in the right `type` and `format` required for the intended analysis.

### Step 4
Performed various analysis on the data and recorded my observations and findings, some of which are listed below:

1. Generated a plot that shows the Top 10 states in terms of Confirmed Covid cases by Laboratory test.
2. Generated a plot that shows the Top 10 states in terms of Discharged Covid cases.
3. Generated a plot that shows the Top 10 states in terms of Deaths from Covid cases.
4. Generated line plots for the different columns of data across the entire recorded period to highlight the rate of total cumulative cases.
5. Determined the daily infection rate.
6. Calculated maximum infection rate in a day and on what date this was registered.
7. Determined the relationship between the external dataset(**Overall community vulnerability index**) and the NCDC COVID-19 dataset.
8. Generated a regression plot between **Confirmed Cases and Population Density** to visualize the linear relationships.
9. Calculated the maximum deaths in a day and on what date this was registered.
10. Generated a regression plot between **Death Cases and Age** to visualize the linear relationships.
11. Analyzed the effect of the pandemic on the country's economy be comparing its RealGDP across the period, as well as the state budgets.


## Suggestions on future work/Improvement plans

To expand upon this project, other external datasets outside what has been used in this project can be explored. More questions can be asked and answered in addition to the analysis done here. 
* Impact of COVID-19 on employment or unemployment statistics.
* Which industries thrived or were in a decline due to COVID-19?
* What goods and services were in high and low demands at the height of the pandemic?
* The effect of Vaccine rollout on number of confirmed cases.
* Comparison of testing capacity in a region versus confirmed cases.
* etc