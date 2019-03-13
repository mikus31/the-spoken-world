# Ruby-Throated Hummingbird Migration Map
Examining open-sourced hummingbird sighting data in North America

## INTERACTIVE RUBY-THROATED HUMMINGBIRD MAP

The idea is to design a map that shows the yearly migration patterns of ruby-throated hummingbirds in North America in an effort to find out how the pattern varies from year-to-year in order to help the map user or audience discern if variables (man-made, environmental, etc.) are affecting yearly migrations.

**Draft Description**

The map will connect points of equal dates, or dates within ranges, to create hummingbird migration contour lines. See the roughly-sketched graphic below:

![hummingbird contours](/images/hbird-contours.png "Hummingbird Contours Map")

After these contour lines are collected and refined, the data can be stylized and the map animated to produce a wave-like effect northward across North America. This animation can be done for each year individually, for all years collectively, or by individual months (see [John Nelson's iceberg map](https://www.esri.com/arcgis-blog/products/arcgis-pro/mapping/iceberg-map-part-2-animation/) for an example). Allow the user to choose the parameters by providing these options. 

This modern, unique way of visualizing the data is designed to enhance the exposure of the data collecting sources and therefore attract more attention and participants in future data collection efforts. In the process, it also may reveal some interesting patterns or anomalies regarding ruby-throated hummingbird northward migrations.

**The Data**

Data from Hummingbirds.net:

  * [Ruby-throated Hummingbird First-bird Reports](http://www.hummingbirds.net/map.html)
  
Data from Journey North:

  * [Hummingbird, Ruby-throated (FIRST)](https://maps.journeynorth.org/map/?map=hummingbird-ruby-throated-first&year=2019)
  
**Inspirations & Ideas**

  * Within this project, create a web map that allows users to collect date of departure data. The above resources do a good job of capturing first sighting data already, but not when the birds are last spotted in an area.
  * Dataviz Idea: Plot the sightings by date by state. Use a scatterplot? Lineplot?  
  * [Iceberg Map: Part 2, Animation](https://www.esri.com/arcgis-blog/products/arcgis-pro/mapping/iceberg-map-part-2-animation/)
  
**Tasks**

  * ~~Rename repo~~
  * Build a web scraper to download the hummingbird sighting data from Journey North for the years 2011--2018
  * Create wireframe for web map
  * Create wireframe(s) for dataviz idea(s)
  * Create web form for capturing last sighting date and location
