# EDA PROJECT

### Identifying and Ranking Post-Pandemic Declines in NYC Subway Ridership

## Abstract

Undeniably, MTA Subway ridership fell off significantly during the COVID-19 pandemic, especially in the city's early crisis months (March - June 2020), a time when many aspects of city life were essentially shut down. As the city reopens, MTA management has grave concerns that daily ridership totals may remain lower than in pre-pandemic years, impacting revenues at a time when the orgaization already faces an ongoing a budget crisis. The goal of this project is to determine which stations have lost the most riders, and also to see if neighborhood income level may be associated with lost ridership. The results will enable MTA to mount a targeted marketing outreach campaign which prioritizes winning back lost riders in the most impacted areas.

## Design

Based on COVID-19 vaccine availability and the New York timeline of reopenings in 2021, this study assumes that the city could be considered fully "reopened" as of May 2021. Thus, the period of study used to determine lost ridership was chosen to be May through June of 2021. The "pre-pandemic" period of interest for the study was May and June of 2019. Note that by choosing the same months for both years, the study avoids potentially deceptive results skewed by seasonal ridership variations which might occur if data from immediately before the pandemic (e.g., January and February of 2020) were chosen instead.

## Data

The data used in this study was drawn from the MTA daily turnstile datasets (http://web.mta.info/developers/turnstile.html), which record the entry and exit counters on every passenger turnstile in every subway station in the city at four hour intervals. This study focused on the entry counters and the associated columns uniquely identifying each turnstile and the date and time of each reading.

The turnstile data was augmented with additional datasets mapping MTA turnstiles to specific station names and MTA complexes (a location housing one or more stations). This data was found here: https://qri.cloud/nyc-transit-data/

Finally, U.S. Census Bureau data on Median Household Income by Zip Code was used to gain some insight into the neighborhoods associated with each station. That data can be found here: https://data.cccnewyork.org/data/table/66/median-incomes#66/107/62/a/a

## Algorithms

As no models were built for this project, no algorithms per se were required. However, standard Pandas slicing, filtering, sorting, merging and aggregation methods were used extensively to clean, explore and visualize the data and present the final results.

## Tools 

The following tools were used in this project:

1. SQLite (to store and preliminarily explore and verify the MTA Turnstile data's integrity)
2. SQLAlchemy (to access the SQLite database and import the MTA Turnstile data into Pandas)
3. Pandas (to import, explore and clean the supplemental MTA station data and US Census Bureau demographic data as well as further explore and clean the MTA Turnstile data, and to create the final dataframes with demographics and Turnstile data combined)
4. Matplotlib and Seaborn to visualize the data and present final results
5. Python 3.8 (to enable the use of Pandas, SQLAlchemy, Matplotlib and Seaborn)

## Communication

In addtition to presenting final Project Slides to the stakeholders, all work (including the slides) can be found here: https://github.com/georgepappy/eda/tree/main/FINAL_PROJECT

