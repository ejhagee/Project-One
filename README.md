# Project-One
A Collaborative Data Visualization Project


# Project Proposal
Our project is to look into U.S. citizens travel trends to international overseas regions from the last 20 years (1996 -2017). We will consider variables such as year and time of year which will lead into other factors such as weather and US economic climate.  Further investigation will proceed into observable trends.

# Questions to Ask of Our Data
1. How has travel numbers changed over time? (Regional distribution changed over months or years?)
2. What may make people travel during certain periods of time?
3. what's the most popular travel destination and the least favorable destination according to the travel trends in the past 20 years? 
4. How the change of economy affect people's purchasing power on traveling overseas?
5. How income affect your travel decision？ （similiar to question #4) 
6. The change on travel numbers during a major historical event/natual disarster/ political crisis. 

# Format layout
The air departure data for outbound U.S. citizen travel comes from the National Trade and Tourism Office ITA research program (https://travel.trade.gov/research/monthly/departures/index.html).  It is located in the "raw downloaded data" folder.  This data was then converted to utf-8 csv's in the "utf-8 csv data folder".
To avoid having to create read/writes for each file, the data was combined into one file "airline_departures_all.csv".  It is located in the main file structure, but more importantly in the "airline data" folder, which also includes cleaned versions of this data, as well as some supplemental data from the Bureau of Transportation Statistics (https://www.bts.gov/content/annual-passengers-all-us-scheduled-airline-flights-domestic-international-and-foreign-1).  This is located in 'domestic_total_airline_travel.csv', but is not included in the main analysis.
The "Transpo data" folder contains data obtained from the National Trade and Tourism Office as well about travel spending (https://travel.trade.gov/outreachpages/outbound.general_information.outbound_overview.asp).  Cleaned versions are also included.
The "economic data" folder contains data on the unemployment rate and median income of the United States.  These are obtained from the Bureau of Labor Statistics and the Census Bureau via the Federal Reserve Bank of St. Louis.  These can be found at (https://beta.bls.gov/dataQuery/find?fq=survey:[ln]&s=popularity:D) and (https://fred.stlouisfed.org/series/MEHOINUSA672N).
The "images" folder contains the saved png charts, as well as one screenshot used in the presentation.
The data cleaning code is in the "data cleaning code" folder.  The final jupyter notebook of interest is the "airline_departures_cleanup.ipynb" file.
The data analysis code is in the misspelled folder, "data analysis coce".  The final jupyter notebook is "Data Analysis.ipynb", which contains the charts generated.
The required write-up is found in the "Write up" folder, while the presentation is in power point form in the "Presentation" folder.  The final version of each will have FINAL in the name.
The main folder contains a couple miscellaneous files as well as the README document.  They are a downloaded data file and a test .txt file to test github commits.
