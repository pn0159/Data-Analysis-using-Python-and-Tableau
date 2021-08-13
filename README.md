# Suicide Rates Analysis

# About the Project

Suicide is one of the major leading causes of deaths. Close to 800,000 people die due to suicide every year, which is one person every 40 seconds and there are many more people who attempt suicide. Suicide occurs throughout the lifespan and was the second leading cause of death. Effective and Evidence-based interventions can be implemented at population and individual levels to prevent suicide and suicide attempts. The goal of my project is to analyze the significant suicide rates trends patterns happening globally and leading cause/methods of suicides. The motivation of this project is a series of suicides happening all around the world without no reason because of depression. The result of this analysis helps the government bodies in understanding on how to bring new laws to reduce the suicide rates and furtherly to enhance already existed laws used in preventing suicide rates.

# Data Source and Data Description

The Dataset used for this project was taken from Kaggle. All the data are stored in a comma separated file with “.csv” as its extension. The dataset gives overview of suicide rates across the globe from 1985-2016. It contains 27820 rows and 10 columns. For this analysis I have used variables : Country, Year, Sex, Age, Suicides_no, Population, Suicides/100k pop, GDP_for_year, GDP_per_capita, HDI for year and Generation.
Link: https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016

This dataset contains the following Columns:

•	Country	           : Indicates Country name. Country of record data

•	Year               : Indicates Year of record data.

•	Sex                : Indicates sex (Male or Female).

•	Age                : Represents the Suicide age range. Ages divided in to six categories('5-14 years','15-24 years','25-34 years','35-54 years','55-74 years','75+ years')

•	Suicides_no        : Number of suicides

•	Population         : Population of the sex, in the age range, country and year.

•	GDP_for_year       : GDP of the country in the year

•	GDP_per_capita     : Ratio between the country’s GDP  and its population

•	Suicides/100k pop  : Number of suicide deaths per 100k individuals in a population

•	HDI_for_Year       : Human Development Index, an index that measures life Expectancy, income and education.   

•	Generation         : Based on age grouping average, it has 6 different categories:‘Generation Z’, ‘Generation X’, ‘Boomers’, ‘Silent’, ‘Millenials’, ‘ G.I. Generation’ 


In addition to this dataset, I have also used the following dataset to elaborate my analysis on leading cause/methods of suicides.

Link: https://ourworldindata.org/suicide#suicide-is-a-leading-cause-of-death-especially-in-young-people

The Firearm suicide dataset contains the following Columns:
	
•	Country	           : Indicates Country name. Country of record data

•	Year               : Indicates Year of record data.

•	Deaths	           : Self harm by Firearm( Deaths per 100k)

The Pesticide Poisoning suicide dataset contains the following Columns:
	
•	Country	           : Indicates Country name. Country of record data

•	Year               : Indicates Year of record data (2014).

•	Share of deaths from pesticide poisoning (%) : Number of Deaths(%)

# Research Questions

1.Who tend to commit suicide more(Generation)?

2.Does GDP_per_Capita have any influence on suicide rates?

3.Visualize the trend of any one major leading suicide method globally ?

4.Which year has the highest suicide deaths by pesticide poisoning?

5.Over the years has the number of suicide rates increased or decreased? Which Year has highest rate?

6.Global Impact-Suicide rate(Deaths per 100k)

7.Which gender has highest suicide rate?

8.Country with High Suicides and Low suicides before 2010.

9.Number of suicides in Russian Federation for 35-54 age group?

# Tool Used
• Tableau 2019.4 version

• Python: Google colab


# Files
Data: suicide-rates.csv

Project:

Suicide Rates_Project.twbx

SuicideRates_Project.ipynb

# Summary 

From the analysis, I can conclude that though the suicide rates have been decreased year by year but still it accounts for nearly 800,000 deaths per year globally. The suicide rates for men are much higher than women and it is clear that this suicide rate was more in the age group 35-54 in men and followed by Teenagers. Earlier this rate was more in G.I.Generation (75+) in 1990s which was later drastically reduced. Number of suicides reduced drastically from 1990 by 2016 as the average GDP_per_capita increases. This shows 
the economic impact of country has on suicide rates. Looking at the annual suicide deaths from firearms across the world tells that Greenland has the highest firearm suicide rate and  60% of firearms deaths in US are from suicides. This warns us that  the respective government bodies should strive forward in reducing the suicide rates by implementing laws and bringing awareness. 30% of suicides globally were the result of pesticide poisoning most in low to middle income countries. This was much higher across western pacific with 48% of suicide rate by pesticide poisoning in 2014. Knowing the differences in risk among the age groups is important for suicide prevention, because teenagers and adults have the highest rate of suicide attempts.
