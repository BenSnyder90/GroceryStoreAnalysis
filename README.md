# GroceryStoreAnalysis
CWRU Data Analytics Bootcamp - Project 1 - Sean Atkins, Valerie Lobas, Ali Rizvi, Ben Snyder

Used Google API data to create heat map of grocery stores available in NorthEast Ohio.
Pulled population, income, and poverty data from Census API. Data collected from 2018 ACS.

Answered the following questions with charts:
Are there any food deserts in Ohio?
Is there a correlation between county population and number of grocery stores?
Is there a correlation between poverty rate and number of grocery stores?
Is there a correlation between average income and number of grocery stores?

Link to Agile Board: https://trello.com/b/BrcSIkk8/griffinpuff-agile-sprint-board
Link to Google Slides: https://docs.google.com/presentation/d/1_0ZVqLlGNhl5VZ7A9H746sWos7xDM4a9OZ0gFLIK3Js/edit?usp=sharing

## Contents
### Project 1 Propsosal.docx
Initial propsal document of the group. Lays out the direction we wanted to go in examining food deserts.

### GoogleAPI_Data_Collection.ipynb
Jupyter Notebook that utilizes the Google Places API to collect store data for various grocery stores, including Name, Lat/Long, Address, County

### Census_Data_Collection.ipynb
Jupyter Notebook that utilizes the Census API to collect population data from the latest available year, which was 2018. Includes data for each county in Ohio of Population, average Income, Poverty count, Poverty Rate

### Data_Cleanup.ipynb
Jupyter Notebook that takes the various CSV files created from data collection and cleans them. We made consistent columns for each store data CSV to be able to merge them. We also had to clean the data, getting rid of potential duplicates or further clarify data taken from the APIs

### Analysis.ipynb
Jupyter Notebook that utilizes gmaps to plot heatmaps of the store data for NE Ohio. It also uses matplotlib and scipy stats to create bar charts and scatter plots as part of our statistical analysis into population data for each county.

### Heatmaps Folder
Screenshots taken of the various heatmaps created from the Analysis notebook

### Output_CSVs Folder
CSV files of store and census data exported by the data collection notebooks

### Project_Data Folder
Various notebooks we worked on during the course of this project

### Matplotlib Charts
PNG images of the stastical analyses we performed on the data. The images are titled according to what data we examined
