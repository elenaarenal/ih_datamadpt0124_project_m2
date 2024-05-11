<p align="left"><img src="https://cdn-images-1.medium.com/max/184/1*2GDcaeYIx_bQAZLxWM4PsQ@2x.png"></p>

# __ih_datamadpt0124_project_m2__

![Image](https://github.com/dataptmad0124/ih_datamadpt0124_project_m2/blob/main/images/visuals.jpg)

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



## __Challenge 1: BI Report/Dashboard__

BI Reports and Dashboards are powerful tools for communicating important information __at-a-glance__. The goal of this challenge is to build a BI Report/Dashboard using a dataset of your choice. Bear in mind the __purpose__ of the report and build a __normalized__ model that fits your visualization requeriments and interactivity performance.

You may use either __Tableau__ or __Power BI__ or __Streamlit__ as your main tool for creating your reporting app. Also you will need to create an ETL process in which you may need to include __data ingestion__, __data transformation__ and __model optimization__ processes.

> __Tip:__ you should first consider which data and which indicators should be put on the BI Report/Dashboard. Then, decompose the key indicators from multiple dimensions. 

<p align="center"><img src="https://media.giphy.com/media/l46Cy1rHbQ92uuLXa/giphy.gif"></p>


A BI Report/Dashboard is not exactly a sequential set of descriptive charts. Instead, a BI Report/Dashboard should be __a single interactive interface built around a specific objetive and which components are logically arranged in order to provide data relevant insights effectively__.



---



## **References:**

- [Visual Analysis Best Practices](https://github.com/ih-datapt-mad/ih_datamadpt0923_project_m2/blob/main/images/visual-analysis-guidebook.pdf)

- [Financial Times Visual Vocabulary](https://github.com/ft-interactive/chart-doctor/tree/master/visual-vocabulary)

- [Tableau](https://github.com/dataptmad0124/lessons/blob/main/m2/_20240420_bi_tableau.md)

- [Power BI](https://github.com/dataptmad0124/lessons/blob/main/m2/_20240424_bi_pbi.md)

- [Streamlit](https://github.com/dataptmad0124/ec_we_love_streamlit)

- [Data Ingestion](https://github.com/dataptmad0124/lessons/blob/main/m2/_20240427_bi_data_ingestion.ipynb)