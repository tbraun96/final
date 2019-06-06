# Web Visualizing a LiDAR Point Cloud in the McDonald-Dunn Forest
### Bryan Begay, Thomas Braun, Katie Nicolato || Oregon State University Cartography and Geovisualization Group

About


Goal (such as, what is the message you want to deliver through the geoviz?)

Our project goal was to visualize a LiDAR point cloud of a forest stand with terrain elements. This project stems from research creating point cloud visualization models to ensure maximized forest aesthetics. Point clouds capture high detail stand structure. Managers can use these models to pre-visualize timber harvests by simulating specific tree removal. An important element for this visualization is terrain. Depending on the terrain and residual structure of the post-harvest stand, it is possible to occlude or hide a timber harvest to increase forest aesthetics. We were initially interested in integrating a forest point cloud with a viewshed analysis tool utilizing terrain. Our base goal was to overlay a point cloud on a 3D terrain map for web visualization. Future development could include a viewshed analysis tool. The project template is transferrable for future forest stand visualization.

Technical summary: You are required to explain (1) system architecture, (2) the main functions of your web map using either screenshots of the web map or a code snippet of the function, and a concomitant description.

Example Potree Conversion command:

```
PotreeConverter.exe assets/merge.las -o web  --projection "+proj=utm +zone=10 +ellps=GRS80 +datum=NAD83 +units=m +no_defs" -o web -p index
```


### Concept

[]!(img/sketch_4.jfif)

Design Scheme (briefly descrption is needed)

Data source

We

Favicon

Applied libraries (e.g., Leaflet, D3, C3) and Web Services (e.g., github, basemap) in use

[GitHub] hosts the visualization.

Credits

Bryan Begay, Thomas Braun, Katie Nicolato (2019)
[Oregon State University Cartography and Geovisualization Group] (https://geoviz.ceoas.oregonstate.edu/)

Acknowledgements

[Dr. Bo Zhao], GEOG 572 Geovisual Analytics Instructor
[Oregon Lidar Consortium]
