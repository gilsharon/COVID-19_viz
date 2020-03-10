
## Visualizing COVID-19 cases data (1/22/20 - 3/10/20)
This is an exercise in plotting data on a map and , hopefully, will add some modeling future trajectories based on the data and compared to China. 

*updating this repo every couple of days*

Source of data: the [Humanitarian Data Exchange](http://data.humdata.org). 
Inspiration for this repo is based on the [Johns Hopkins CSEE visualization](https://data.humdata.org/dataset/novel-coronavirus-2019-ncov-cases#metadata-0)

All Python 3 based - pandas, numpy, geopandas, imageio.  

* to do: 
    * Incidence / Prevalence
    * SIR (Susceptible, Infected and Recovered) modeling
    * Visualize active cases (total - recovered) and mortalities on map
    * ~~add country names to lineplots~~
    * ~~change case number annotations to color~~
    * ~~US specific maps~~
    * ~~Dont disply animations on Readme.MD (still in figures)~~ 
    * ~~Cumulative cases in log scale~~
    
Findings so far are pretty scarry.. 
**Cases in the US on map.**
![Case by Map](/figures/forReadme/USMap_3-9-20.png)

**Mortalities in the US on map.**
![Case by Map](/figures/forReadme/USMap_mortalities_3-9-20.png)

**Cases by country on map.**
![Case by Map](/figures/forReadme/worldMap_2020-03-09.png)

**Cumulative cases by country by date**
![Cumulative Cases](/figures/forReadme/cumulativeCases_logScale.jpg)

**Total cumulative cases and countries with at least one novel case by date**
![Cumulative Countries](/figures/forReadme/cumulativeCountries.jpg)

