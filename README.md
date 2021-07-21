# Python Project - Prediction of Solar Energy Production using Machine Learning

## **OVERVIEW**

Steadily growing for several years, renewable energy now represents more than 21% of total electricity production in 2019 in France (RTE). As an important part of renewable energy, solar PV represents 10.1% of gross renewable electricity generation. 
With the advantage of being cleaner than traditional energy sources like coal or oil comes multiples challenges: 
Electricity produced from renewable sources is very difficult to store. Batteries and other storage capacities are not mature enough technologically speaking. The power is handled smartly over “grids” that would redirect supply where the demand lies on the network.  
- Overproduction results in loss of money. 
Renewable energies are directly dependent on the weather which is dynamic and complex to forecast.

- Shortage of power due to lack of sun radiation results in inconvenience for clients, a fine from the government and impact on provider reputation.     

This calls for an accurate forecast and management of energy production based on external conditions. 

## **OBJECTIVES**
- Develop a solar energy forecast model to predict three-hourly solar energy production of Île-de-France region in France  
- Compare different models for solar energy prediction

## **SPECIFICATIONS**
### **Data collection**
1. [Commission de régulation de l'énergie (CRE) Open Data](https://www.cre.fr/Pages-annexes/open-data)
    - Electricity production by source by region in France from 2013 to Nov. 2020 with several measurement per day: [Données éCO2mix régionales consolidées et définitives (janvier 2013 à novembre 2020)](https://opendata.reseaux-energies.fr/explore/dataset/eco2mix-regional-cons-def/table/?disjunctive.libelle_region&disjunctive.nature&sort=solaire)
    - Solar radiation and wind speed by region in France 3-hourly from 2016: [Rayonnement solaire global et vitesse du vent à 100 mètres tri-horaires régionaux (depuis janvier 2016)](https://opendata.reseaux-energies.fr/explore/dataset/rayonnement-solaire-vitesse-vent-tri-horaires-regionaux/information/?disjunctive.region&sort=date)
2. [Historical hourly weather data - Station Paris Montsouris](https://www.ncei.noaa.gov/access/search/data-search/global-hourly?bbox=51.091,-4.777,41.367,9.553&place=Country:146&stations=07156099999)

### **Methodology / Tools**
- Time series: 
  - SARIMAX
  - FB Prophet             
- Machine Learning: 
  - Lasso Regression
  - Elastic Net
  - Random Forest Regression
  - XGBoost
- Deep Learning:
  - ANN
  - LSTM
  - CNN+LSTM

