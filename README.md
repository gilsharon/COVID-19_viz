# COVID-19_viz

## Visualizing COVID-19 cases data
This is an exercise in plotting data on a map and , hopefully, will add some modeling future trajectories based on the data and compared to China. 

Source of data: the [Humanitarian Data Exchange](http://data.humdata.org). 
Inspiration for this repo is based on the [Johns Hopkins CSEE visualization](https://data.humdata.org/dataset/novel-coronavirus-2019-ncov-cases#metadata-0)

All Python 3 based - pandas, numpy, geopandas, imageio.  

* to do: 
    * Incidence / Prevalence
    * SIR (Susceptible, Infected and Recovered) modeling
    * Visualize active cases (total - recovered) and mortalities on map
    * add country names to lineplots
    
Findings so far are pretty scarry.. 

** Cumulative cases by country by date (you can guess which is China) **
![Cumulative Cases](/figures/forReadme/cumulativeCases.jpg)

** Cumulative countries wish at least one novel case by date**
![Cumulative Countries](/figures/forReadme/cumulativeCountries.jpg)

** Cases by country on map. **
![Case by Map](/figures/forReadme/worldMap_2020-03-03_optimized.gif)
