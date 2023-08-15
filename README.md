# Top 50 Most Visited Countries Database - Data Visualization Project

## Project Overview:
This project aims to provide a comprehensive database for understanding the top 50 most visited countries in the world. The dataset includes various factors such as affordability, number of UNESCO Heritage Sites, safety, infrastructure, income group, and more. The database serves two purposes: 

1. To facilitate the analysis of patterns and characteristics behind the most visited countries.
2. To act as a guide for travelers seeking to choose a tourism destination based on specific criteria.

Data was collected from different sources, including Kaggle for the most visited countries dataset, web scraping using BeautifulSoup for safety information and number of UNESCO Heritage Sites, and the Travel & Tourism Development Index from the World Travel Organization for additional variables.

The collected data was cleaned and merged into the "tourism_database" table, which was then uploaded to an SQL database. 

## Purpose of the Data Visualization Project:
The purpose of this data visualization project is to visually explore the collected data, identify trends, and analyze patterns that characterize the most visited countries in the world. By enriching the analysis with additional variables, the project aims to provide further insights into what makes these countries popular destinations.

To achieve this, two new categories were added to the dataset, obtained from the World Economic Forum Tourism Development Index. The data was cleaned and transformed using the "tourism_notebook.pynb" notebook, resulting in the "tourism_index.csv" file. This file was then imported into Tableau for visualization.


The Tableau visualizations consist of several dashboards, organized into a cohesive story. The project findings reveal significant insights regarding the most visited countries, their characteristics, and potential correlations among the analyzed variables. Some of them will be detailed below:



- In this page we can visualize the most visited countries and regions, as well as the leading nations amongst these. Clearly, the Europe and Eurasia region dominates the global tourism industry concentrating more then half of all tourism inflows. France, Spain and the United States are the top 3 global destinations by number of arrivals. In total, the top 50 most visited nations concentrate around 90% of global tourism.

  

<img width="1212" alt="Screenshot 2023-08-15 at 15 44 37" src="https://github.com/rodrigogtz99/w5-project_visualizacion/assets/139127453/cd7e2133-761c-4c77-b426-3e7382ffad34">



- In this second group of visuals, we can see how almost 70% of global tourism is concentrated in high-income economies. That proportion goes up to 90% if upper-middle income economies are included. The remaining percentage is shared primarily by lower-middle income economies while the lowest income percentile has no representatives in the top 50 most visited countries. On the right, the most visited nations divided by income groups are made visible.

  

<img width="1186" alt="Screenshot 2023-08-15 at 20 03 18" src="https://github.com/rodrigogtz99/w5-project_visualizacion/assets/139127453/5467a31f-5793-4b9c-b110-2339f81ed739">



- In this third visualization, a Pearson correlation analysis is made between the number of arrivals and each of the indicators used in this study, including UNESCO sites, natural resources, tourism infraestructure, international openness, etc. The purpose of this was to see which of the different asepcts which characterize a destination seem to have the strongest correlation with an increase in the number of inbound arrivals. The findings reveal that the number of cultural sites (measured by number of UNESCO World Heritage Sites), the amount of natural resources, tourism infraestructure and international openness (in this order) seem to be the main factors which determine how much a country is visited. On the other hand, aspects such as affordability, government support (through campaigns, etc) and sustainability have the least positive correlation with the number of arrivals, in fact, the correlation is minimally negative. 


<img width="1053" alt="Screenshot 2023-08-15 at 20 16 14" src="https://github.com/rodrigogtz99/w5-project_visualizacion/assets/139127453/ca28e40f-4362-4223-a4a3-4c0e049a2b10">


- In the following two pages, the previously mentioned correlations can be seen more clearly. Ordered in descending order by the most influential factors mentioned above, a pattern can be seen. The countries in the highest rankings of the number of cultural sites, the amount of natural resources, tourism infraestructure and international openness tend to be highly positined in the number of received  tourisits (as is portrayed by the blue color scale).
  

<img width="1074" alt="Screenshot 2023-08-15 at 20 28 21" src="https://github.com/rodrigogtz99/w5-project_visualizacion/assets/139127453/62ff8b36-7236-4b6a-a062-fd1d71479619">



<img width="1091" alt="Screenshot 2023-08-15 at 20 48 24" src="https://github.com/rodrigogtz99/w5-project_visualizacion/assets/139127453/6d3ab9b1-46e0-4ad2-98b7-b31ccf0f1ffb">



- Lastly, it appears that affordability is less influential that what could have been expected. In fact, most of the most visited countries are considered expensive when compared to the lower end of the list. Also, safety, another commonly perceived travel consideration seems not to play a key role in the number of arrivals. It does so in a minnimal extent, leaving out very conflictive nations from the list. However, countries like Turkey, France, Mexico and the United States are at the top of the list with considerable levels of unsafety. 


<img width="1094" alt="Screenshot 2023-08-15 at 20 33 39" src="https://github.com/rodrigogtz99/w5-project_visualizacion/assets/139127453/7391ade4-dbe7-444b-87e0-c03ad94532c8">



## Conclusion:

With a database which comprises almost 90% of global tourism, it can be inferred that a considerable amount of economic well-being, a high number of cultural and natural landmarks, a considerable level of tourism infrastructure, and an openness to the world are the factors which seem to characterize the countries which have succeeded in becoming the global hubs for tourism. On the other hand,another key finding is that factors such as affordability seem to be less important than what is commonly inferred. 

For the detailed data visualizations and findings, please refer to the public link provided in the "visualization link.txt" file.
