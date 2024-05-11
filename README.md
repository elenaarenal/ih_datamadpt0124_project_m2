

# Project Module 2


Climatic change is one of the biggest challenges that human race will face in the near future. The following dashboard will show you the anañysis of the last 10 years with regards to gas emissions (methane, CO2, fluorinated gases and NO2), climatic policies & initiatives adopted by states, global-warming related catastrophes around the world.


## **Status:**

As the data is limited and we do not haven proper meassures so far, the project is in its initial status. It will be improved as far as significant datas will be provided.The data we have used is from mid 2014 to mid 2024  (first and last year have been removed from some of the visualizations as the data is not complete and it cannot be compared with the rest of the data from full years)


---
### Technology stack
For the development of this project, the following libraries/imports have been used in our jupyter notebook are :

    pandas
    numpy
    duckdb
    os
    
    
As data sources, we have used several csv with the abovementioned information:
'climate_forecasts.csv',
 'climate_initiatives.csv',
 'climate_observations.csv',
 'climate_policies.csv',
 'climate_research.csv',
 'climate_stakeholders.csv',
 'environmental_impacts.csv',
 'greenhouse_gases.csv',
 'natural_disasters.csv',
 'regions.csv'


**Aspects that have been considered**:

   Eventhough a data base has been created useing Duckdb, as the analysis & dashboard has been performed in Tableau, we have not used it.

  All the csv have a common key: city_id, wich has been extremely usefull to cross all data
  
  Longitud and latitude in data was wrong (not matching). Therefore, for all the geolocalization, new generated latitudes&longitudes has been created.
   


 **Tableau**
 
 Visualizations has been done using Tableau Public
 We can focus in the gas emission data (total) and methane emission. Some of the datasets has not been used as they nor provide significant information.
        




## **Db diagram:**

![db_diagram.jpg](attachment:db_diagram.jpg)



## __How to navegate it__

Open tableau public through the following route:

https://public.tableau.com/app/profile/elena.arenal/viz/Project2_17152762649850/Top10

The document contains 14 sheets and *5 dashboards to navegate* :

    -Total gases emitted by continent & year

    -Ranking of most and less polluting countries in the world by total gas emission

    -Methane (CH4) emission worldwide

    -Maximum temperatures worldwide by continent and year (ºC)

    -Percentage of Natural disasters & initiatives by continent

---
## **Data Obtained:**

You can navegate through the sheets through filters & animations. Select the parameters you are interested in (e.g: total gas emission worldwide in 2016)

![image.png](attachment:image.png)
![image-2.png](attachment:image-2.png)

## **Limitations and improvements to be made :**

Cross with real data
More detailed datasets
More years to analyse: climat change is a long term issue
