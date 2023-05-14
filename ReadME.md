

# Flood Modeling using Random Forest

This project is a machine learning model built using different APIs to source data. The goal of this project is to predict the likelihood of flooding in a particular area based on certain topographial and environmental factors such as landuse, slope and elevation.

## Project Outlines

* An introduction to the project and question being answered (e.g.: what areas are susceptible to flooding)

* Details on the dataset on which the discovery is being performed (dependent variable) (e.g.: source, data, projection, format and what processing might have been done on it)

* Data preprocessing details on the independent variables that are included, including source and why it was selected)

* The task that has been selected and why, e.g: are you performing classification or regression

* The selection of the algorithm and why, e.g.: CART, random forest, etc.

* Running the algorithm and any hyper-parameterization

* Evaluation of the results – include accuracy, ROC-AUC, and at least one other measure from the confusion matrix and explain what they     represent

* Finally, run the model on-some untrained data and present the results in a map


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.##

### Prerequisites

You will need the following tools:

* Python 3.7 or higher
* Pip package installer
* Jupyter notebook or any other suitable IDE

### Installing

Follow the below steps to install and run the project:

1. Clone the repository to your local machine
```
git clone https://github.com/SammyGIS/Flood-Modeeling-using-ML.git
```

2. Install the required packages using pip
```
pip install -r requirements.txt
```

3. Open Jupyter notebook or any other suitable IDE and run the notebook `floood_prediction.ipynb`

## Built With

* [Python](https://www.python.org/) - Programming language used
* [Pandas](https://pandas.pydata.org/) - Data manipulation library
* [Scikit-learn](https://scikit-learn.org/stable/) - Machine learning library
* [Geopandas]
* [Rasterio]


## Acknowledgments

* Kumar, D., Tiwari, P. C., & Rastogi, A. K. (2018). Flood susceptibility mapping using remote sensing and machine learning techniques: A review. Remote Sensing Applications: Society and Environment, 10, 1-23.

* Sarpong, F., Li, J., & Li, Z. (2020). Application of machine learning algorithms in flood susceptibility mapping: A review. Journal of Hydrology, 587, 125040.

* Wang, W., Zhang, C., Li, J., & Zou, L. (2019). Flood Susceptibility Mapping Using Machine Learning Approaches and Sentinel-1 Data. Water, 11(7), 1369.

* ESA WorldCover v200. (n.d.). Google Earth Engine. February 25, 2023, from https://developers.google.com/earth-engine/datasets/catalog/ESA_WorldCover_v200#bands

* Geemap. (n.d.). GitHub. Retrieved February 25, 2023, from https://github.com/giswqs/geemap/blob/master/examples/notebooks/geemap_and_earthengine.ipynb#scrollTo=No26yd0bcRZ1

* Hatarilabs. (2020, January 15). How to reproject single and multiple rasters with Python and Rasterio [Tutorial]. February 25, 2023, from https://hatarilabs.com/ih-en/how-to-reproject-single-and-multiple-rasters-with-python-and-rasterio-tutorial

* Sudipta, P. (2021, May 20). Zonal statistics with Google Earth Engine. Retrieved September 15, 2021, from https://geemap.org/notebooks/12_zonal_statistics/

* World Bank. (n.d.). Import and export data [Tutorial]. Retrieved February 25, 2023, from https://worldbank.github.io/OpenNightLights/tutorials/mod3_7_import_export_data.html

* Wang, X., Liu, Y., & Zhou, Y. (2019). Towards urban flood susceptibility mapping using machine and deep learning models [Blog post]. Hydroinformatics. Retrieved September 15, 2021, from https://medium.com/hydroinformatics/towards-urban-flood-susceptibility-mapping-using-machine-and-deep-learning-models-3-random-9fe4e1279f3b