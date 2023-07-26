# QGIS-Daily-Challenge
100-day challenge emphasizing on enhancing my skills in Spatial Analysis through the use of QGIS with Python!

My background:
• Accomplished and earned a certificate of completion for the Learning QGIS course from LinkedIn Learning
• Read the book, Learn QGIS-4th Edition by Andrew Cutts and Anita Graser

```bash
'July 5, 2023' DAY 1-Airport Clusters in Alaska Project

Main Map:
• Established concrete airports vector data as a heatmap and point cluster.
  Moreover, reduce its opacity to uncover parcels map of Alaska.
• The parcels map of Alaska is created from gradient fill
• Added grid lines

Title:
• used HTML to generate proper formatting and show accurate date in profile
```

```bash
'July 6, 2023' DAY 2-Spatial Analysis and Python
```

```bash
'July 22, 2023'
DAY 1-Alaska shp.file
• Clipped raster and vector layers
- 2 layers | raster | extraction | clip by mask layer | input layer
- note: doesn't work all the time, check this again

DAY 1-Buildings Found in Downtown, Vancouver
• Extracted data from OpenStreetMap
- installed the plugin, Quick OSM -> select a data value (e.g. building) -> select canvas extent
- for selecting a specific area: select features | add new temporary layer | paste
• Rearranged attribute table in QGIS
- installed the plugin, refractor fields
• Deleted Columns in attribute table
- toggle editing mode | delete fields | shift and manually select fields
• Designed labels in a new map
- item properties | columns
```

```bash
'July 23, 2023' - Dining Adventures! Project
• Created a .csv file that consists of my favorite restaurants in Downtown, Vancouver
- obtained lat and long coordinates through Google Earth Pro
- transform coordinates from EPSG:4326 WGS 84 to ESPG:3857 using epsg.io link
*note: find a better way to get accurate coordinates
- Added labels and set different symbols using a SVG marker
• Used OpenStreetMap in creating a .shp file layer for specific buildings in the map
```

```bash
'July 24, 2023'
• Only have selected streets with attributes included
- select features by freehand | export | save selected feature as | _put location_ | ok
```
