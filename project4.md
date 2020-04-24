# Project 4: Rendering Topography

#### In this project, we will add produce some 3-D plots for our combined adm2s. Using our knowledge of where Urban Areas are located, we will also add our urban areas, road networks, and healthsites to our 3-D plots to ensure that our findings are consistent with our results in project 3.

After cropping the topographic raster based on our combined adm2s borders, we will get the following topographic plot. 

![](1_topo_cut.png)

Using our combined adm2 data from project 3, we will produce a plot only containing the political boundaries of the combined adm2s, without any backgrounds or labels. Below you can find the dotted plot of the political boundaries of the combined adm2s. 

![](2_only_borders.png)

Use the border object to add it on the top of cropped topo plot. 

![](2_topo_cut_borders_shown.png)

Using our combined matrix, we will produce a 3-D plot showing the topographic details of the combined adm2s.

![](3_initial_3d.png)

Next, using the combined matrix and the political boundaries object, a 3-D plot showing the borders of the combined ad2ms is produced:

![](4_borders_shown_3d.png)

We should import the urban areas polygons from project 3 to add it to our 3-D plot. The political boundaries are also added to identify the combined adm2s. 

![](5_only_borders_with_urban_areas.png)

![](6_urban_areas.png)

![](8_roads_urban_areas.png)

![](7_urban_areas_healthsites.png)

![](9_roads_healthsites_urban_areas.png)

![](10_primary_urban_area.png)

![](11_all_together.png)




