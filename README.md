# Air (Ine)quality in America - Metis Intro to Data Science Final Project

Who breathes dirty air in America and where are they located? This project explores the problem of inequality in air quality in America using unsupervised learning. Specifically this project seeks to gain insight into whether or not counties with similar air quality share other similar socio-economic characteristics using K-means clustering. After determining the number of clusters, I use the Python `plotly` library to create a colormaped representation of where counties in each of these clusters are located to offer further insight into their geographic characteristics. 

To conduct this analysis I collected data from the US Environmental Projection Agency (EPA), Census Bureau and Department of Agriculture (USDA). 

EPA data: https://aqs.epa.gov/aqsweb/airdata/download_files.html#Annual

Census data: https://web.archive.org/web/20150821182814/http://quickfacts.census.gov/qfd/download/DataSet.txt 
- codebook https://web.archive.org/web/20150821061818/http://quickfacts.census.gov/qfd/download/DataDict.txt

USDA data: https://www.ers.usda.gov/data-products/county-level-data-sets/
