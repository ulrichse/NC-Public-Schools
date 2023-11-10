# <span style= "color:red">Map of NC Public Schools & Districts</span>🏫

<iframe src="index.html" height="500" width="500"></iframe>

You can explore this map [as its own web page here](index.html).

#### <span style= "color:navy">Lab 06 Deliverable for GHY 5818</span>
Sarah Ulrich

<img src= "https://upload.wikimedia.org/wikipedia/commons/thumb/b/bb/Flag_of_North_Carolina.svg/2000px-Flag_of_North_Carolina.svg.png" width=250/>

This bivariate choropleth map shows the location of all public schools and the boundaries of all school districts in North Carolina, U.S.A. Schools are differentiated by level of instruction and districts are shaded based on total student enrollment numbers from 2019. 

#### <span style="color:navy">Functions</span>

This map uses JavaScript to add school point locations and school district boundary polygons to a basemap, and then add a popup providing the name of each school and district when clicked by the user. Functions in JavaScript added a color fill to the district boundary polygons based on total school enrollment for 2019, and then differentate the color of school location symbols based on school type (elementary, middle, high, or other). A legend created in JavaScript provides information to the user on the map's symbology. Attribution information was also added in JavaScript. 

Within the "<style>" tags, this map uses CSS to format the color and style of the text used in popup and legend features. 

## <span style="color:gold">Data & Libraries</span>
The basemap used in this project came from the Leaflet library. 
<a href="https://www.w3schools.com/cssref/index.php"><span style="color:#339966">W3Schools</span></a> for CSS styling functions. 
<a href="https://fontawesome.com/">Font Awesome</a> used to for school location markers. 
<a href="https://gka.github.io/chroma.js/">Chroma.js</a> used to manipulate icon colors. 
Color palettes from <a href="https://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3">ColorBrewer</a>.
Text font from <a href="https://fonts.google.com/">Google Fonts</a>.
School location data are sourced from <a href="https://www.nconemap.gov/datasets/dea6ff0e8b4743a0ba361e13a85a4c70/about">NC OneMap</a>. 
<a href="https://catalog.data.gov/dataset/tiger-line-shapefile-2017-state-north-carolina-current-unified-school-districts-shapefile-state">North Carolina school district boundaries</a> are from the U.S. Census Bureau Department of Commerce. 
Enrollment data are from the <a href="https://nces.ed.gov/">National Center for Education Statistics</a>.
