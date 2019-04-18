# THE SPOKEN WORLD
An interactive worldwide map of place name pronunciations.

## Mapping Project Proposal

**Introduction**

The inspiration to design and create a map that allows users to click on a place in the world and hear its pronunciation came to me from a 9-year-old's homework assignment. My cousin Asher had a geography project due for school, and he chose to author a report about Iceland. I traveled to Iceland a few years ago, so naturally Asher thought I could help him with the pronunciation of Icelandic places.

![iceland homework](/images/ashers-homework.png "Asher's Geography Homework")

And discouragingly I could not help him! This problem bothered me relentlessly for a few days, until I had the idea to make a map to help Asher and others learn how to pronounce world place names.

Think about the importance of place names for a second. What we name our places matters deeply to all of us on a local level. It speaks to our culture, and it tells the rest of the world something about us. But how we pronounce our places is just as important too, and indicative of our geographical identity.

For example, take the city of New Orleans. There are a number of pronunciations of New Orleans out there in the world, including:

* new or-leenz
* new or-lee-inz
* [new ahl-e-yuns](https://www.businessinsider.com/how-locals-pronounce-city-names-2014-9-2) 
* naw-linz
* new or-linz

However, only one of these pronunciations is acceptable on the local level: The latter pronunciation. A New Orleanian can tell if you are (a) likely from the city or (b) likely a tourist immediately by how you pronounce New Orleans.

Pronunciation is personal, and it is local. It also is a global phenomenon, in that this anecdotal example of New Orleans plays out all over the globe across all scales of geography. This mapping project is an effort to elevate local, authoritative pronunciations to the global level.

**Methodology**

Anticipated data sources include the following:

* [Wikipedia](https://commons.wikimedia.org/wiki/Category:Pronunciation_of_names_of_cities)
* [Natural Earth](http://www.naturalearthdata.com/)
* [NGA GEOnet Names Server](http://geonames.nga.mil/gns/html/index.html)
* [Equal Earth Area Projection](https://observablehq.com/@d3/equal-earth)
* [inogolo](https://inogolo.com/)
* [Forvo](https://forvo.com/)
* [Pronounce](https://pronounce.voanews.com/index.php)
* [howjsay](https://howjsay.com/)
* [The Name Engine](https://www.thenameengine.com/category/On%20The%20Map/226)

Anticipated tools for data manipulation and analysis include the following:

* QGIS
* Microsoft Excel
* Python
* Jupyter Notebook
* Pandas
* Geopandas

Front-end data for the web map will be produced as a GeoJSON-CSV stack.

The web map will be accessible via a web browser on both desktop and mobile devices. The anticipated technology stack for the web map is HTML-CSS-JS-Leaflet, as well as any necessary JS libraries. For example, the web map will need a library for its universal search functionality.

![uni search bar](/images/search-bar.png "Universal Search Bar Mockup")

Data on the map will be visualized as polygon and point features. A muted, mono-color styling will be applied to continent-level polygon features. A classified choropleth styling will be applied to country-level polygon features, as in a political map. Point features will be symbolized proportionally by population size.

Users will be invited to interact with the map immediately on the splash page. The search bar will feature prominently on the center of the screen, encouraging users to begin by typing in a place name. Alternatively, the user will be given the option to explore the map manually by clicking a button beneath the search bar to bypass the search functionality.

![desktop splash page](/images/splash-page-mockup.png "Splash Page on Desktop")

After zooming into the map to the country level, place names will appear. Users will be able to click on these place names. A popup will appear with information about the place, including a pronunciation file that can be played.

![iceland with sound icons](/images/ice-with-sound.png "Iceland")

Aesthetically, the plan is to use web applications to drive the design of the map. Anticipated web apps to include the following:

* [ColorSupplyyy](https://colorsupplyyy.com/app)
* [Google Fonts](https://fonts.google.com/)

The overall aesthetic will be a simple design with bright, contemporary colors and modern, complementary fonts. The user will be given the option to toggle between light and dark modes.

**Conclusion**

In college, my wife Sarah did a National Student Exchange program at the University of Hawaii-Hilo one semester. She learned about Hawaiian food and culture while on the "Big Island" and also a little about Hawaiian language. When I told her about this project, she mentioned that Hawaiians can discern what island a fellow Hawaiian is from by how they pronounce place names.

Place names are personal to all of us, both in terms of what names are chosen for places and how we pronounce those names. Names and their pronunciations are local. And at the same time, though it seems contradictory on the surface, global as well.

---
*Mapping project proposal by Michael McNeil for [New Maps Plus](https://newmapsplus.as.uky.edu/) at the [University of Kentucky](http://www.uky.edu/UKHome/).*
