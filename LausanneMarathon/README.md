# About this repository
The main objective of this repository is to reveal the diversity of nationalities of runners who participated in Lausanne Marathon 2018. This analysis could be:
- Helpful to decide whether a special support for specific languages, e.g., translation for a web site, is needed.
- Useful to explore the possibility of regarding a marathon race as the opportunity for tourism business.

# Results
Main results are summarized in [my Tableau Public page](https://public.tableau.com/profile/kotaro.sonoda#!/vizhome/LausanneMarathon/dashboard)

Supplementary figures are available in the Jupyter Notebook: [2018_DataVisualization.ipynb](https://github.com/ksonod/my_projects/blob/master/LausanneMarathon/2018_DataVisualization.ipynb)
* Choropleth map cannot be shown on GitHub. If you run codes in the Jupyter Notebook, you can see the map shown below:
<img src="https://i.imgur.com/cOdHOFE.png" width="400px">   

# Methods
- Web scraping
- Data cleaning
- Data visualization (matplotlib, folium, Tableau)
- SQLite for creating a database

# Contents
- <strong>[2018_WebScraping.ipynb](https://github.com/ksonod/my_projects/blob/master/LausanneMarathon/2018_WebScraping.ipynb)</strong>: After running all cells in this notebook, you can scrape web data and get the collected data as csv files and a database.  
-  <strong>[2018_DataVisualization.ipynb](https://github.com/ksonod/my_projects/blob/master/LausanneMarathon/2018_DataVisualization.ipynb)</strong>: Data are taken from the created database and visualized using matplotlib and folium. 
- <strong>world-countries.geojson</strong>: Geojson file for showing a map.
- <strong>output</strong>: In this folder, the scraped data are stored as csv files and a database.

# Data source
- [IOC country code](https://raw.githubusercontent.com/johnashu/datacamp/master/medals/Summer%20Olympic%20medalists%201896%20to%202008%20-%20IOC%20COUNTRY%20CODES.csv)
- [ISO country code](https://raw.githubusercontent.com/lukes/ISO-3166-Countries-with-Regional-Codes/master/all/all.csv)
- [Marathon data](https://services.datasport.com/2018/lauf/lamara/)
