1. In the reading for Tuesday and today (Stevens et al.) the authors use a technique to produce a high resolution description of the 
distribution of uman populations across the globe. What is the name of the technique and describe in general and basic terms how it works?

There are several methods that attempt to disaggregate census data for
finer scale, gridded population data sets, but the authors present a new semi-automated dasymetric 
modeling approach called "Random Forest." This approach incorporates detailed census and ancillaries 
and combines widely avaiable, remotely-sensed and geospatial data that contribute to the modeled 
dasymetric weights and then use the Random Forest model to generate a gridded prediction of population
density. This approach is extremely flexible, allowing for incorporating global, large scale data sets
of both continuous and discrete covariates when finer finer scale data do not exist to are diffcult 
to process over large areas. 

2. The random forest method used by the authors is a machine learning algorith (ensemble method) In 
general terms, what is a machine learning algorith? Within the context of this study what distinguishes 
a data science, machine learning method from previous classical statistical approaches to describing
and analyzing phenomenon and events?

Machine learning is an AI ability that enables systems to automatically learn from previous experiences
without being manually programmed. In other words, in a machine learning process, the system relies on
itself to improve the functionality and workability of the program. Random Forest model is also a 
machine learning method that determines population density weightings, which is more effective
in describing and and analyzing covariates of both a discrete and continous nature than the previous
classical statistical approaches. The classical statistical approaches relied on manual programming
which itself has an increaed chance of error in calculations. Random Forest, however, relying on its own
is a more accurate model to describe population density weightings. The approach
benefits from non-parametric statistical predictions based on the best ancillary data available,
but also anchors those predictions across space to the best available, contemporary administrative boundary-linked GIS census data.

3. In the reading, the authors use a number of geospatial covariates as predictors in their machine
learning method. What were these geospatial covariates and approximately how big of a data set did
they represent (in general terms) what is the significance of big data in the estimation of machine 
learning methods for inferring the correlates and drivers of human population distribution. 

Based on the reading, the vector and raster class-based data, (e.g. individual land cover classes, water bodies, protected area presence/absence, etc.) are then converted to binary masks, creating a binary covariate. The data size was approximately 100 meter by 100 meter pixels. THe significance of big data in the estimation of machine learning is the enabling context of it. Big data classes
enable scientists to easily analyze and describe population distribution. Moreover, big data classes improves the machine learning as
well, because the more data we have, the more experienced the algorith becomes. 

4. The authors' results present a remarkable improvement over previous geospatial descriptions at
very high resolution, of the distribution of the human population. Within the context of human 
development in LMICs, what is the significance of having a highly accurate description of where
each person is located across planet earth?

Per author descriptions, high resolution and contemporary data on human population distributions are
vital for measuring impacts of population growth, monitoring human-environment interactions and for 
planning and policy development. Accurate spatial data sets that represent the distributions of human populations are critical in
many health, economic, and environmental fields across various temporal and spatial scales. Considering an estimated world population increase of 2.3 billion people between 2011
and 2050, with more than 50% of that growth absorbed into urban areas, the ramifications
of having accurate population information has never been more important



5. Within the context of human development in LMICs, what is the relevance to your area of investigation in having a highly accurate 
description of where each household and person is located across planet earth?

If scientists have the knowledge of where each household and person is located across planet earth, they can easily map population
distributions. Having a highly accurate, and descriptive population distribution map can be crucial in interpretation of other geospatial data that will be used by local officials to take census. It can be also used by the analyst to confirm if the population
distribution map really matches the actual and real-world data that we have. 




