# Apartment_Rental_Germany
Personal Project about Rental Apartment in Germany Prices Analysis from a dataset scraped from Immoscout24 website
### Table of Contents

1.  [Project Motivation](#motivation)
2.  [Methods Used](#method)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Project Motivation<a name="motivation"></a>

In this project, I will use the Apartment rental offers in Germany data available on Kaggle, scraped from www.immobilienscount24.de to analyse the real estate market in Germany. I will conduct EDA to understand the dataset and I will be using regression ML technique to see if we can predict total rent amount. Then, Kmeans unsupervised ML techniques will be applied to identify clusters within the dataset. Furthermore, geospatial analysis for the German rental market will be conducted by creating a choropleth map.  Lastly, I will be sourcing Consumer Price Index data for Germany from Quandl API and conducting time-series analysis and forecasting.

## Methods Used <a name="method"></a>
- Exploratory data analysis to understand the dataset
- Feature selection and elimination using Correlation 
- Using Machine Learning model for prediction
- Use Kmeans Unsupervised ML Technique for Clustering
- Conducting a geospatial analysis for the German rental market by creating a choropleth map
- Time series analysis and explore forecasting process

## File Descriptions <a name="files"></a>
1. `Project Management` : Notebook containing the Project Brief
2. `Data` : contains the data sets, `Original` and `Prepared`
3. `Scripts` : jupyter notebook files containing all the codes for the whole project combined including EDA & Machine learning model
4. `Analysis` : `Reports` and `Visualization`
5. `Sent to client`: contain Dashbord send to client

## Results<a name="results"></a>
- The prediction and clustering, can be found on the `Scripts`files.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
The data belongs to www.immobilienscount24.de and is for research purposes only. You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/corrieaar/apartment-rental-offers-in-germany). The time series data are obtained from [Quandl](https://data.nasdaq.com/) and the GeoJSON file containing geo-coordinates of Germany for geospatial visualization are obtained from [here](https://github.com/isellsoap/deutschlandGeoJSON). Otherwise, feel free to use the code here as you would like! 
