# Final Project: Gabon
##### My final project on Gabon
##### By Sayyed Hadi Razmjo
##### W&M 2023

## Administrative subdivisions of Gabon
Gabon is a country on the west coast of Central Africa with an area of nearly 100,000 sq mi and 
population of 2.1 million people. Gabon has 9 provinces which are then divided into another 37 departments:
1. Estuaire (Libreville) - Captial province
2. Haut-Ogooué (Franceville)
3. Moyen-Ogooué (Lambaréné)
4. Ngounié (Mouila)
5. Nyanga (Tchibanga)
6. Ogooué-Ivindo (Makokou)
7. Ogooué-Lolo (Koulamoutou)
8. Ogooué-Maritime (Port-Gentil)
9. Woleu-Ntem (Oyem)

![](Gabon.png)

Let's explore Gabon's least developed and least populated province: Nyanga

#### Southern Gabon Coast (Nyanga County)
Nyanga is the southernmost of Gabon's nine provinces. The provincial capital is Tchibanga, which had a total of 31294 inhabitants in 2013. Nyanga is the least populated province of the nine and one of the least developed despite being the southern coast of Gabon with sea ports and trade routes. The Atlantic ocean is located on the western side of Nyanga, making it an strategically important province. Nyanga is divided into 3 districts: Douigny, Basse Banio, and Nauti Banio which is then divided into 6 other sub-departments. 

![](Gabon_stretch_goal_2.png)

#### Nyanga County with two other Eastern Gabon States
The Ogooué-Lolo Province is one of the nine provinces of Gabon, slightly southeast of central Gabon. It has a total area of 9,800 sq mi. The regional capital is Koulamoutou, a city of approximately 16,000 people. It is the ninth largest city in Gabon and the home of slightly more than one-third of the provincial population.
The Ogooué-Ivindo province is the northeastern-most of Gabon's nine provinces, though its Lopé Department is in the very center of the country. The regional capital is Makokou, which is home to one-third of the provincial population. It gets its name from two rivers, the Ogooué and the Ivindo. This province is the largest, least populated, and least developed of the nine.

![](Gabon_stretch_goal_3.png)


## Population distribution across Gabon's subdivisions
We will analyze population distribution in Gabon for two different levels:

#### Population distribution across Gabon's first administrative levels (provinces):
Gabon has a total of 2.1 million population with Libreville in Estuaire being the most populated city with 703,940 people living in it. As obvious on the map, the western coast of Gabon is a major trade center and that is the reason western coast cities and provinces have relatively more population than central and eastern provinces of Gabon. Gabon's economy is mostly dependent on oil reserves which is concentrated in western cities. Haut-Ogoouie, eastern border of Gabon, having the famous Mpassa river crossing it, is a trade route to Republic of Congo, a major customer for Gabon's oil reserves. This clearly proves the fact that people have populated the major cities and have left the central part of Gabon relatively vacant. In fact, Central Gabon has one of the least population density across the region. This also shows the spread of poverty in Gabon. The richest 20% of the population earn over 90% of the income while about a third of the Gabonese population lives in absolute poverty.

![](Gabon_population_map.png)

#### Population distribution across Gabon's second administrative levels (districts):
As previously mentioned, the western coast of Gabon is heavily populated due to its proximity to big waters. The Estuaire province, the capital of Gabon, is home to more than 700,000 people. The eastern coast of Gabon is less populated compared to the western coast. This map shows the population distribution over Gabon's districts with light red showing the districts with the least population and dark red representing the districts with the highest populations. Per population map, Komo-Mondah is the most populated district which is located in the Estuaire province, the capital of Gabon. Mpassa district, Franceville, located on the eastern part of Gabon, is also highly populated. Franceville is one of the four largest cities in Gabon, with a population of around 110,568 people. It lies on the River Mpassa and at the end of the Trans-Gabon Railway and the N3 road, which is the reason that Mpassa district is a trade center in Gabon. Central districts are almost evenly populated which clearly shows a pattern of even resource distribution in central Gabon. 

![](project_1_part2_stretch_goal_1.png)

#### A 3-D visualization of population distribution in Gabon:

![](Project_1_part2_stretch_goal_3.gif)

#### Population distribution calculated as a percentage for each subdivision:
In the following geometric bar, you can find out how each subdivision accounts for the total population of Gabon:

![](project_1_part3_Ordered_filled_geom_bar.png)

#### Population Density in Gabon's each first subdivision (province):

![](project_1_part3_population_map_with_density.png)

#### Population Density in Gabon's each second subdivision (districts): 
This geometric bar shows the population distribution over Gabon's districts. The density of Komo-Mondah district, located in capital Liberville, Estuaire, simply outweighs almost 7 other provinces based on its density. This single district is denser than all other 7 provinces. It is almost twice as denser as Haut-Ogoouie province, one of the most important provinces in Gabon.

![](project_1_part3_stretch_goal_1.png) 

#### Using Linear Modeling To Analyze Population Distribution

The histogram below is desired to show population distribution accross different adm2s. In my adm2 sf object I now have 28 variables including the topo, ntl, and slope covariates. To start my description and analysis of the land use and land cover data, I first consider the pop19 variable created in the last project.

![](project2_part1_hitogram.png)

This plot shows density based on log of the population accross adm2. 

![](project2_part1_density.png)

Now that we have plotted different covariates with wrapping pop19 around it, we will regress the data from multiple variables against each other and examine the correlationship that is being described by the variables. For example, in the following plot, I have estimated a regression model where the population of Gabon in 2019 is the dependent variable, while night time lights (ntl), urban cover (dst190), and bare cover (dst200), topo, slope, dst(010), dst(011), dst(130), dst(140), and other covariates are the independent variables (predictors). This plot highlights all the outliers including Komo-Mondah that is a striking outlier, separated from the rest of the regression model and data. We will also calculate F-statistics and R-adjusted Squared for the linear model. The plot below does a linear model estimation of population distribution based on night time lights data gathered from online resources. 

![](project2_part1_stretch_goal_adjust.png)

#### Let's subset Mpassa and explore differences between our linear model estimation and the actual Data from the WorldPop website.
This original raster object downloaded from the WorldPop website shows the original population distribution:
![](project2_part3_actual_population_worldpop.png)
However, after subsetting Mpassa and investigating its population distribution, I found out that my linear model actually overpredicts Mpassa's population distribution in some areas. The following 3-D plot shows the striking overprediction in the central areas of Mpassa, Francesville: 

![](project2_part2_Mpassa_3d_plot.PNG)

To get a better visualization, consider the following mapview of Mpassa:

![](project2_part2_Mpassa_mapview.png)
