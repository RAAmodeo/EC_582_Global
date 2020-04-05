# EC_582_Global
Course project materials for Economics of Globalization with Professor Anca Cristea, Winter 2020.

## Question at Issue
Is there a relationship between crime rates and attitudes toward globalization (eg. trade liberalization, immigration)? That is, as people are statistically more or less safe, do they feel more or less open to dealing with people and businesses from other countries?

This report examines potential relationships between local crime levels and public sentiment toward globalization.  

Though the consensus among researchers has been that rates of crime are not impacted by changes in levels of globalization, US political debate of globalization remains rife with emotional arguments capitalizing on public safety concerns.
Much work has been done around the question of whether crime rates increase with increasing levels of globalization, yet government policies around globalization issues of trade liberalization, immigration, and financial integration are often guided more by emotion than rationality.  

## Data
Data applies to the United States.

### Crime Rates
Crime rates constructed by dividing total number of named crime category by population for each county in each year. Crime level data was gathered from the FBI’s Uniform Crime Reporting (UCR) data and aggregated at the county-level annually for 1970 – 2017. 
County population-by-year data gathered from https://data.nber.org/data/census-intercensal-county-population.html for 1969 - 2014. 

#### Crime Data Caveat
Data on crime levels are difficult to understand in general. Reasons for this include that crime is enforced unevenly across cultures and regions (and certainly varies across the USA); the enforcement (i.e. reporting) changes over time, activities and statuses determined to be criminal also change over time. In addition to those reasons, many instances of crime go unreported by victims, let alone are “proven” to be crimes. The time series crime data used in this analysis pertain to “actual” crimes according to FBI standards of reporting.

### Public Sentiment
Public sentiment data is gathered from General Social Survey (GSS) data aggregated at the county-level annually for 1972 – 2018. 

Specifically, a question on whether economic growth (often linked with immigration and trade liberalization) always has a negative impact on the environment was asked in four surveys from 1993 through 2010. A question on whether trade unions are needed to protect workers was asked in seven surveys between 1989 and 2018. The question of whether the respondent is in favor of or against the government supporting declining industries to protect jobs was asked five times 1985 through 2016. Eight surveys asked the respondent’s feelings on the level of immigration to the U.S. 1996 through 2016. Thirty-one surveys years 1973 through 2018 asked respondents both whether they think the US is spending too much money on it, too little money, or about the right amount on halting the rising crime rate and on foreign aid.

#### Sentiment Data Caveat

Many questions whose responses could give much insight were asked in only one or two survey years. Sentiment data used in this analysis are from questions asked over at least four surveys. 

Participation in GSS surveys does not require answering all questions. Many survey respondents skipped the questions I examine. While we do not know why individuals opt out of certain questions, we are safe to treat the choice as endogenous to the overall social attitude of the survey taker and possibly also to the survey interviewer. Though anonymity is part of the GSS reporting, the fact that a person with the survey interviews the respondent may influence respondents to skip controversial questions if they believe or fear their feelings may be judged or be outside the social norms. 

### Trade Openness

Trade openness data gathered from the World Bank’s records of World Bank national accounts data and OECD National Accounts data files, aggregated at the national level annually for 1970 – 2018.


## old notes
County-level FBI UCR data 1960 - 2017.

County-level GSS data on public sentiment toward issues of globalization.
Search all GSS variables available here: https://gssdataexplorer.norc.org/variables/vfilter?utf8=%E2%9C%93&user_search_id=&state_id=&search_type=&keyword=&doslider=1&yrmin=1972&yrmax=2018&years=&subjects=&ssearch=&commit=SEARCH

* GSS data will limit timeframe because sentiment data was not collected in all years.


Measures of trade openness from the World Bank: https://data.worldbank.org/country/united-states and https://data.worldbank.org/indicator/NE.TRD.GNFS.ZS?end=2018&locations=US&start=1970&view=chart


Can I figure out a simple way to get this sentiment data in a processable form? https://www.pollingreport.com/trade.htm

## Literature

The role of sentiment in politics and more generally in situations where plenty of data is available to thoroughly refute our beliefs.

Consensus that levels of trade liberalization and immigration do not influence US crime rates.

## Changes over time
looking at:

murders per capita (in county-year)

mean and median on sentiment data in county-year


## Output
15-page paper
