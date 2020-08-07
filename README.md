# National Travel & Tourism Infrastructure Strategic Plan (NTTISP)
This repo is part of a project to develop a National Travel & Tourism Infrastructure Strategic Plan (NTTISP) as part of the directives from the FAST Act. This work was done while working with the National Advisory Council on Travel & Tourism Infrastructure (NACTTI). 

Although the actual strategic plan covers travel and tourism by all modes, this repo has data in 3 areas:
1. Airplane Travel (FAA)
2. Rail Travel (Amtrak)
3. Interstate Highway Travel


# 1) Airplane Travel
 The FAA folder shows the data cleaning and visualization of FAA flight data and forecasts. Forecasts are taken from publicly available enplanement information from FAA's [data website.](https://taf.faa.gov)

## Visuals Shown

1. [2018 Enplanements](https://ericenglin.github.io/FAA-Flight-Visual/Visuals/Enplanements2018.html)
2. [2018 Enplanements Grouped by Hub](https://ericenglin.github.io/FAA-Flight-Visual/Visuals/Enplanements2018-Hub.html)
3. [Scatter Plot of Historic vs Forecasted 20-Year Growth](https://ericenglin.github.io/FAA-Flight-Visual/Visuals/HistoricvsForecasted-Hub.html)
4. [Similar but slightly different scatter plot](https://ericenglin.github.io/FAA-Flight-Visual/Visuals/scatter_GrowthByEnplanements.html)

# 2) Rail Travel 
The Amtrak folder is a web scraper to download PDFs on Amtrak usage at stations across the U.S. from 2012-2018. PDFs are available at the [Rail Passengers Statistics Site](https://www.railpassengers.org/tools-info/ridership-statistics/). Raw PDFs were downloaded at the station level and the state level (both csv's included here). From there, the program will scrape the graph for the last 6 years of ridership from each PDF document. Some stations have discontinued services in the last 6 years, and the program will flag these stations. Final data is posted as data visuals.

# 3) Interstate Highway Travel

The Rest Areas folder is a web scraper for the interstate rest areas around the United States. These are tracked by Roundabout Publications on their [site](https://www.interstaterestareas.com/) by state and interstate. 
