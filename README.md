# KIT MICMoR SummerSchool 2019
![](./images/logos.jpg "MiCMOR, KIT Campus Alpin")

Notebooks and info for the **[MICMoR](https://micmor.kit.edu) [SummerSchool "Environmental Data Science: From Data Exploration to Deep Learning"](https://micmor.kit.edu/sites/default/files/MICMoR%20Summer%20School%202019%20Flyer.pdf)**, IMK-IFU KIT Campus Alpin, Sept. 4 - 13 2019, Garmisch-Partenkirchen, Germany.  

This course covers the PyData stack and setting up a Data Science-centric development environment, good practices in reproducible science and the handling of common data formats. It then goes into Explorative Data Analysis techniques and effective visualisation, Machine Learning methods and finally applications of Deep Learning models for various Environmental Science tasks.   

## Timetable

![Timetable of the summerschool](./images/timetable_eds_2019.png "Timetable")

## Notebooks

### Introductions

| Notebook         | Topic             | Description         |
|------------------|-------------------|---------------------|
| [01_intro_python.ipynb](nbs/01_intro_python.ipynb)| Python basics | A general intro to Python concepts |
| [02_intro_numpy.ipynb](nbs/intro_02_numpy.ipynb)| Numerical computation | A short introduction into key numerical python concepts |
| [03_intro_matplotlib.ipynb](nbs/03_intro_matplotlib.ipynb)| Plotting | The basic plotting facility in Python |
| [04_intro_pandas.ipynb](nbs/04_intro_pandas.ipynb)| Tabular data  | The library to handle tabular data in python |
| [05_intro_xarray.ipynb](nbs/05_intro_xarray.ipynb)| Gridded data  | A great package to handle gridded data (based on numpy and pandas, uses netCDF as backend |
### Data formats, ETL and visualization



### Classical Machine Learning

### Deep Learning

## Datasets

This is a list of datasets we will work with in this course.

|Name|Source|Description|Use for|Comment|
|:--|:--|:--|:--|:--|
|tree occurrence|UCI|Predict tree occurrence based on |ML/ DL(tabular)|[source](https://archive.ics.uci.edu/ml/datasets/covertype)|
|amazon satellite classification|kaggle|Multi-objective classification|DL |[source](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space) |  
|forest fire BA prediction |UCI | Regression on forest fire dataset | ML | [source](https://archive.ics.uci.edu/ml/datasets/Forest+Fires) |  
|plants|UCI|clustering ? | ML | [source](https://archive.ics.uci.edu/ml/datasets/Plants) | 
|water treatment plant| UCI | clustering ? | ML | [source](https://archive.ics.uci.edu/ml/datasets/Water+Treatment+Plant) |  
|GHG observing network| UCI | multi-variate time-series | TS | [source](https://archive.ics.uci.edu/ml/datasets/Greenhouse+Gas+Observing+Network) | 
|lightning strikes| NOAA | available via thredds server url | ? | [source](https://www.ncei.noaa.gov/thredds/catalog/lightning/catalog.html) |  

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cwerner/kit_micmor_summerschool_2019/master?filepath=nbs%2F01_introduction.ipynb)
