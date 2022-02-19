# Covid-19 Analysis to visualize and understand the pandemic cases using different Techniques. 

Coronavirus disease 2019 (COVID-19) time series lists confirmed cases, reported deaths, active cases and comparison with other Epidemics. 
Data are disaggregated by country (and sometimes subregion). 
Coronavirus disease (COVID-19) is caused by the
[Severe acute respiratory syndrome Coronavirus 2 (SARS-CoV-2)](https://en.wikipedia.org/wiki/Severe_acute_respiratory_syndrome_coronavirus_2) and has had a worldwide effect.

This notebook uses data from various sources to understand, analyze and visualize the changes in the number of cases through different visualization techniques and plots.

This dataset includes time-series data tracking the number of people affected by COVID-19 worldwide, including:

- confirmed tested cases of Coronavirus infection
- number of people who have reportedly died due to Coronavirus
- number of people who have reportedly recovered from it

## Notebook Demo

[](https://user-images.githubusercontent.com/56031116/153548747-e7461c4c-a8c6-428b-ac5f-b181856e4174.mp4)

## Executed Cells from the Notebook
Checkout the Notebook with all the executed cells to see the results for each plots in this Html version of the notebook @[Notebook](https://parthd06.github.io/Covid-19Analysis/). 

**Please note this file takes a lot of time to load & view, hence it is preferred that you watch the above video or execute the Notebook on your local Machine.**

### **Note**:
The Data collection for **Recovered cases** isn't quite accurate and has been stopped by a lot of countries and it is also found discrepancies in data if taken from multiple sources. Also a lot of recovery cases aren't reported and it is not possible to analyze them accurately. Yet the data reported till July 2020, is quite accurate to understand. You can select from Jan2020 to Jan 2021 to clearly see the transition in all the graphs.  

Therefore the following two scenarios should also be kept in mind:
- Active Cases are calculated based on recoveries so this will not be also correct
- Anything that requires recoveries in the calculation isn't accurate, like deaths/100recoveries, etc.

**Additional References** for the above point:
- https://www.dallasnews.com/news/public-health/2020/05/19/why-arent-coronavirus-recoveries-always-reported/
- https://abc11.com/nc-coronavirus-recovery-cases-update/6127051/

Most of these reports are based on the US but mostly it is true for the rest of the world.

## Sources for DataSet

The following datasources are used:

- World Health Organization (WHO): https://www.who.int/
- DXY.cn. Pneumonia. 2020. http://3g.dxy.cn/newh5/view/pneumonia
- BNO News: https://bnonews.com/index.php/2020/02/the-latest-coronavirus-cases/
- National Health Commission of the People’s Republic of China (NHC): http://www.nhc.gov.cn/xcs/yqtb/list_gzbd.shtml
- China CDC (CCDC): http://weekly.chinacdc.cn/news/TrackingtheEpidemic.htm
- Hong Kong Department of Health: https://www.chp.gov.hk/en/features/102465.html
- Macau Government: https://www.ssm.gov.mo/portal/
- Taiwan CDC: https://sites.google.com/cdc.gov.tw/2019ncov/taiwan?authuser=0
- US CDC: https://www.cdc.gov/coronavirus/2019-ncov/index.html
- Government of Canada: https://www.canada.ca/en/public-health/services/diseases/coronavirus.html
- Australia Government Department of Health: https://www.health.gov.au/news/coronavirus-update-at-a-glance
- European Centre for Disease Prevention and Control (ECDC): https://www.ecdc.europa.eu/en/geographical-distribution-2019-ncov-cases
- Ministry of Health Singapore (MOH): https://www.moh.gov.sg/covid-19
- Italy Ministry of Health: http://www.salute.gov.it/nuovocoronavirus

## Screenshots

### Dataset Preparation

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss1.png?raw=true">

### WorldWide Confirmed, Recovered Cases & Deaths

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss2.png?raw=true">

### Scatterplot

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss3.png?raw=true">

### Case Density

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss4.png?raw=true">

### Case over a period of Time 

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss5.png?raw=true">

### Case Visualization using Folium Maps

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss6.png?raw=true">

### Choropleth Maps

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss7.png?raw=true">

### Confirmed & Death Cases using Bar plot

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss8.png?raw=true">

### Static Color Maps

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss9.png?raw=true">

### Death & Recoveries per 100 Cases

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss10.png?raw=true">

### No. of new cases per Day & Countries

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss11.png?raw=true">

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss12.png?raw=true">

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss13.png?raw=true">

### Scatterplot for Deaths Vs Confirmed Cases

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss14.png?raw=true">

### Bar plot

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss15.png?raw=true">

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss16.png?raw=true">

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss17.png?raw=true">

### Line plot

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss18.png?raw=true">

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss19.png?raw=true">

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss20.png?raw=true">

### Growth rate after 100 cases

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss21.png?raw=true">

#### Growth rate after 1000 cases

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss22.png?raw=true">

#### Growth rate after 100K cases

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss23.png?raw=true">

#### Growth rate after 1 Million cases

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss24.png?raw=true">

#### Growth rate after 10 Million cases

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss25.png?raw=true">

### Tree Map Analysis

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss26.png?raw=true">

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss27.png?raw=true">

### First & Last case report time

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss28.png?raw=true">

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss29.png?raw=true">

### Confirmed cases Country & Day wise

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss30.png?raw=true">

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss31.png?raw=true">

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss32.png?raw=true">

### Covid-19 Vs other Epidemics

<img src="https://github.com/parthd06/Covid-19Analysis/blob/main/Screenshots/ss33.png?raw=true">
