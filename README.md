1.0	Problem Statement and Background
Research Question:
I will investigate the relationship between socioeconomic factors and violent crimes in the U.S. at the national level.
1.	How does median household income influence violent crime rates across counties?
2.	How does the percentage of the population with a bachelor’s degree or higher influence violent crime rates across counties?
Dependent Variable:
•	Violent crime rate per 100,000 people. 
o	Homicide, rape, robbery, and aggravated assault.
Independent Variables:
•	Median household income (ACS)
•	% of the population with a bachelor’s degree or higher (ACS)
ML Framework:
•	Regression Model to predict violent crime rates using socioeconomic indicators.
•	Classification model to categorize counties into “High Crime,” “Medium Crime,” or Low Crime” groups based on thresholds of violent crime rates.

Reasoning and Hypothesis
Understanding the relationship between income, education, and crime can help policymakers target interventions like poverty education, job creation, and education access as indirect strategies for crime prevention.
Hypotheses:
•	Counties with higher household incomes will have lower violent crime rates
•	Counties with higher educational attainment will have lower violent crime rates.
By applying regression and classification models, I expect to find negative correlations between socioeconomic indicators and violent crime.
Dataset Description and Details
1.	American Community Survey (ACS) 5-Year Estimates (2019–2023)
o	Description: Nationwide survey conducted by the U.S. Census Bureau that provides county-level demographic, social, and economic data.
o	Key Columns: Median household income, % of population with bachelor’s degree or higher.
o	Usage: These socioeconomic indicators will serve as predictors of county-level crime.
o	Source/Provenance: https://data.census.gov/table/ACSST5Y2023.S1501
2. FBI Crime Data Explorer (Uniform Crime Reporting Program)
•	Description: Repository of official violent crime statistics reported by law enforcement agencies across the U.S.
•	Key Columns: County, violent crime rate per 100,000 people, including homicide, robbery, rape, and aggravated assault.
•	Usage: This dataset provides the dependent variable to be modeled and analyzed.
•	Source/Provenance: CDE
US Census Demographic Data
Crime in Context, 1975-2015

