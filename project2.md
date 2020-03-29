# Project 2: Using Linear Modeling To Analyze Population Distribution
### Sayyed Hadi Razmjo

This Projects Has 3 Parts:

## Part 1
Extracting Land Use and Land Cover Data for Description

This histogram is desired to show population distribution accross different adm2s. Since the numbers are very big, the log function is used to scale them according to the x-axis. 
![](project2_part1_hitogram.png)

This plot shows density based on log of the population accross adm2. 
![](project2_part1_density.png)

Notice that the density plot has a similar profile as the histogram.  We can compare the two by overlapping the histogram with the density plot or probability density function. 
![](project2_part1_density&histogram.png)

This plot does a linear model estimation of night time lights based on where the population is distributed. 
![](project2_part1_ntl&pop19.png)

This plot shows how density changes based on where night time lights all over Gabon's subdivisions. This Residual model with regression line represents the correlation of night time lights, urban cover, and bare cover with Gabon’s population distribution.

![](project2_part1_ntl.png)

![](project2_part1_all_together.png)

This plot highlights all the outliers including Komo-Mondah that is a striking outlier that is separated from the rest of the regression model and data.  
![](Error_with_text.png)

## Part 2: Modeling & Predicting Spatial Values
#### Finding population and differences between our linear model and the actual WorldPop raster information
Our model is serving to allocate population totals across all gridcells, but how accurate is it?  To start we can calculate the different of our predicted values - the worldpop values and sum the totals. Here are the plots that shows how different our model is different than the actual values from the Worldpop website. As obvious our model shows that on the western coast of Gabon, where its capital is located, the population distribution is extremely uneven. In fact, the capital subdivision has as many population as all subdivisions combined. 
![](project2_part2_diff.png)
![](project2_part2_diff_pop.png)


## Subsetting "Komo-Mondah" population and differences between our linear model estimation and the actual Data.
Gabon's capital, Libreville, is located in Komo-Mondah subdivision. Since we don't have access directly to map Libreville, we will subste Komo-Mondah subdivision and plot its population distribution
![](project2_part2_Mondah_diff.png)
![](project2_part2_Mondah_pop.png)


#### A 3-D plot representing population of Komo-Mondah
![](project2_part2_Mondah_3d_plot.PNG)


#### A Mapview of Komo-Mondah
![](Project2_part2_Mondah_mapview.png)


## Subsetting "Mpassa" population and differences between our linear model estimation and the actual Data.
Mpassa is Gabon's other populated subdivision. It is populated due to the Mpassa River running accross it. Historically, people tend to live close to waters. Since Gabon's economy relies on agriculture, most people prefer living near to waters. Below are plots for Mpassa's population distribution and the difference between our model estimation and the Worldpop data.
![](project2_part2_Mpassa_diff.png)
![](project2_part2_Mpassa_pop.png)


#### A 3-D plot representing population of Mpassa
![](project2_part2_Mpassa_3d_plot.PNG)


#### A Mapview of Mpassa
![](project2_part2_Mpassa_mapview.png)


