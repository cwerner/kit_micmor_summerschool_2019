# KIT MiCMOR SummerSchool 2019
![](./images/logos.jpg "MiCMOR, KIT Campus Alpin")

Notebooks and info for the **[MiCMOR](https://micmor.kit.edu) [SummerSchool "Environmental Data Science: From Data Exploration to Deep Learning"](https://micmor.kit.edu/sites/default/files/MICMoR%20Summer%20School%202019%20Flyer.pdf)**, IMK-IFU KIT Campus Alpin, Sept. 4 - 13 2019, Garmisch-Partenkirchen, Germany.  

This course covers the PyData stack and setting up a Data Science-centric development environment, good practices in reproducible science and the handling of common data formats. It then goes into Explorative Data Analysis techniques and effective visualisation, Machine Learning methods and finally applications of Deep Learning models for various Environmental Science tasks.   
 
# TODOs
## General
### Urgent stuff
> "Things that should be clarified really soon!"  

- [ ] Video recordings
	- [ ] Inform lecturers and ask permission, also clarify the copyright restrictions on slides
	- [ ] Check with A. Fischer (KIT) about technical details
	- [ ] Check with Uwe about local requirements  
	- [ ] Check with R. Kiese if we have a HiWi that would be interested in doing recordings
- [ ] Mail lecturers about repository, planned schedule and timelines   
- [ ] Initiate weekly meetings with K. Fuchs to push on and keep momentum 
- [ ] Student poster notification eMail (1/2 summary, 1/2 data used, required) 

### Resolve soon
> "These can take a bit longer (but not too long)..."  

- [ ] Setup GCP instance/ docker image for course (should be one image that is also deployed to GCP) 
- [ ] Schedule some dates to test-drive the notebooks with PhDs at IFU

## Admin tasks
> "Administrative stuff that needs fixing/ clarification."  

- [ ] Wifi situation in lecture room (setup local access points and local network?)
- [ ] Saturday activities in addition to BYO data (some hiking suggestions, etc.)


## Datasets
> "Which datasets could we use for the notebooks?" 

Ideally, we'd want some IFU datasets that are relevant for a number of participants. Also, we should check with lecturers if they have pet datasets that make sense and fit their topics/ tools.

|Name|Source|Description|Use for|Comment|
|:--|:--|:--|:--|:--|
|tree occurrence|UCI|Predict tree occurrence based on |ML/ DL(tabular)|[source](https://archive.ics.uci.edu/ml/datasets/covertype)|
|amazon satellite classification|kaggle|Multi-objective classification|DL |[source](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space) |  
|forest fire BA prediction |UCI | Regression on forest fire dataset | ML | [source](https://archive.ics.uci.edu/ml/datasets/Forest+Fires) |  
|plants|UCI|clustering ? | ML | [source](https://archive.ics.uci.edu/ml/datasets/Plants) | 
|water treatment plant| UCI | clustering ? | ML | [source](https://archive.ics.uci.edu/ml/datasets/Water+Treatment+Plant) |  
|GHG observing network| UCI | multi-variate time-series | TS | [source](https://archive.ics.uci.edu/ml/datasets/Greenhouse+Gas+Observing+Network) | 
|lightning strikes| NOAA | available via thredds server url | ? | [source](https://www.ncei.noaa.gov/thredds/catalog/lightning/catalog.html) |  
