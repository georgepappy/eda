# PROJECT PROPOSAL

##### IN 2021, WITH NEW YORK CITY NOW REOPENED, HAS MTA SUBWAY RIDERSHIP DECLINED RELATIVE TO PRE-PANDEMIC LEVELS? IF SO, DO SPECIFIC STATIONS AND NEIGHBORHOODS EXHIBIT AN INORDINATE DECLINE IN RIDERS, AND ARE THERE ANY PARTICULAR DEMOGRAPHIC TRENDS OR PATTERNS ASSOCIATED WITH THESE NEIGHBORHOODS?

Undeniably, MTA Subway ridership fell off significantly during the COVID-19 pandemic, especially in the city's early crisis months (March - June 2020), a time when many aspects of city life were essentially shut down. As the city reopens, MTA management has concerns that daily ridership totals may remain lower than in pre-pandemic years. Worried about a sustained loss of revenues, the organization has expressed interest in finding out which stations have been most affected. For these, MTA would like to know more about the associated neighborhood demographics so that a targeted marketing outreach campaign can be mounted to win back lost riders in the most impacted areas.

Since the initial shutdown, elementary schools have reopened (December 7, 2020), followed by Middle Schools (February 15, 2021) and High Schools (March 30, 2021). Moreover, most city residents have become eligible for COVID-19 vaccination (March 30, 2021 for anyone 30 or over, April 6, 2021 for anyone 16 or older, and May 10, 2021 for anyone 12 or over). And during this time, most public-facing businesses have reopened. Thus, it would be reasonable to consider New York City to be largely reopened as of May of 2021. 

The "reopened" period of interest for this study will be May and June of 2021. MTA daily ridership totals (as counted by Turnstile data on entries to and exits from all stations) will be determined during this period and compared to the same totals for May and June of 2019 (and perhaps May and June of 2018). These earlier date ranges represent daily ridership totals during the pre-pandemic period. 

Note that by choosing the same months for recent pre-pandemic years, the study will avoid potentially deceptive results skewed by seasonal ridership variations which might occur if data from immediately before the pandemic (e.g., January and February of 2020) were chosen instead. 

Moreover, the comparable data from May and June of 2020 (when the city was fully shut down) will also be included in the study since it may offer some insights into the demographics of specific neighborhoods where riders did or did not have the luxury of staying home and/or avoiding public transportation.

In addition to the MTA turnstile data mentioned above, the analysis will be augmented with selected New York City demographic data from the U.S. Census Bureau (Household Income, Poverty, Educational Attainment Level, Limited English Proficiency) which can be matched to station locations and neighborhoods (referred to as Community Districts by the Census Bureau). Specifically, this will allow daily ridership totals (and associated demographics) to be evaluated at a few different granularities:

- Borough Level (excluding Staten Island, which has no subway lines)
- Community District Level (e.g., Astoria, Bensonhurst; allows for a finer-detailed analysis of demographics)

The tools required for this project are: 

1. SQLite (to store and preliminarily explore, clean and verify the MTA Turnstile data)
2. SQLAlchemy (to access the SQLite database and import the MTA Turnstile data into Pandas)
3. Pandas (to import, explore and clean US Census Bureau demographic data as well as further explore MTA Turnstile data, and to create the final dataframes with demographics and Turnstile data combined)
4. Matplotlib and Seaborn to visualize the data and present final results
5. Python 3.8 (to be able to use Pandas, SQLAlchemy, Matplotlib and Seaborn)

The Minimum Viable Product for this project will be a collection of graphs (e.g., bar charts) showing comparisons of pre-pandemic vs. current ridership, broken down by various demographic criteria. Specific graphs will be used to highlight the significant demographics associated with neighborhoods and stations suffering the most severe loss of ridership in 2021.

