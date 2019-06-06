## Web Visualizing a LiDAR Point Cloud in the McDonald-Dunn Forest
##### Bryan Begay, Thomas Braun, Katie Nicolato || Oregon State University Cartography and Geovisualization Group

#### About


#### Goal

Our project goal was to visualize a LiDAR point cloud of a forest stand with terrain elements. This project stems from research creating point cloud visualization models to ensure maximized forest aesthetics. Point clouds capture high detail stand structure. Managers can use these models to pre-visualize timber harvests by simulating specific tree removal. An important element for this visualization is terrain. Depending on the terrain and residual structure of the post-harvest stand, it is possible to occlude or hide a timber harvest to increase forest aesthetics. We were initially interested in integrating a forest point cloud with a viewshed analysis tool utilizing terrain. Our base goal was to overlay a point cloud on a 3D terrain map for web visualization. Future development could include a viewshed analysis tool. The project template is transferrable for future forest stand visualization.

#### Technical Summary

*System Architecture*

*Functions* of your web map using either screenshots of the web map or a code snippet of the function

Example Potree Conversion command:

```
PotreeConverter.exe assets/merge.las -o web  --projection "+proj=utm +zone=10 +ellps=GRS80 +datum=NAD83 +units=m +no_defs" -o web -p index
```

#### Concept

![](/img/viewshed_sketch_1.JPG)
![](/img/final_site.JPG)

#### Design Scheme

#### Data Source

[Oregon Department of Geology and Mineral Industries (DOGAMI) Lidar Viewer](https://gis.dogami.oregon.gov/maps/lidarviewer/)

#### Libraries and Web Services

[Potree Converter](https://github.com/potree/PotreeConverter) transforms the LAS cloud file into a web-friendly format.
[Cesium ion](https://cesium.com/) hosts the terrain map 
[GitHub](https://github.com/) hosts the visualization.

#### Credits

Bryan Begay, Thomas Braun, Katie Nicolato (2019)</br>
[Oregon State University Cartography and Geovisualization Group](https://geoviz.ceoas.oregonstate.edu/)

#### Acknowledgements

[Dr. Bo Zhao](https://ceoas.oregonstate.edu/profile/zhao/), GEOG 572 Geovisual Analytics Instructor, Oregon State University</br>
[Oregon Lidar Consortium](https://www.oregongeology.org/lidar/)
