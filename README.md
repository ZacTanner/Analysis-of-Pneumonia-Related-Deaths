# Analysis-of-Pneumonia-Related-Deaths

This data set was obtained from the [World Health Organization’s (WHO) website](https://gateway.euro.who.int/en/indicators/hfamdb_711-deaths-pneumonia/#id=31141). It catalogues pneumonia related deaths across Europe from 1979 to 2022, and data fields include year of death, country, sex (male/female), and number of deaths per year. Pandas (Python) was used for data cleaning and preliminary EDA.

The WHO dataset did not feature population-adjusted metrics, so I downloaded country-wide population estimates from the [European Union’s Eurostats resource](https://ec.europa.eu/eurostat/databrowser/explore/all/popul?lang=en&subtheme=demo&display=list&sort=category) to add further insight. The population estimates dataset was melded and joined to the WHO pneumonia data set, using country and years as keys.

In Tableau, I created several calculated fields to quantify pneumonia death rates, which better convey the frequency of deaths relative to a country’s population. I then developed a choropleth map, pie chart, and bar & line graphs to more clearly illustrate the population-adjusted distribution of pneumonia deaths across countries, years, and sex.

My Tableau Dashboard that further delves into the pneumonia data can be viewed [here](https://public.tableau.com/app/profile/zach.tanner/viz/PneumoniaRelatedDeathsinEurope/Dashboard#1).
