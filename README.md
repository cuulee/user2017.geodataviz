Geospatial Data Visualization using R
=====================================

The goal of user2017.geodataviz is to privide a comprehensive overview of the options available in the R language for Geospatial data visualization. This tutorial covers ...

-   R Packages

-   R Data Structures for Spatial Data

-   Operations Supported on Spatial Data

-   Visualizing Spatial Data

-   Using Base Graphics
-   Using `ggplot2` and helper packages
-   Using `shiny` for dynamic mapping
-   Using `leaflet` and related packages for interactive maps.
-   Using specialized packages such as `tmap`, `choroplethr`, `ggmap`, `plotly`, `highcharter` etc.

Slides
------

The tutorial overview and the slides can be found [here](https://bhaskarvk.github.io/user2017.geodataviz/).

Installation
------------

### The Docker way

The easiest option is using a docker image built specifically for this tutorial.

-   Install [docker](https://store.docker.com/search?type=edition&offering=community), and [docker toolbox](https://www.docker.com/products/docker-toolbox) (only for Windows and Mac).

-   Either using the kitematic GUI tool or command line pull the `bhaskarvk/rgeodataviz` image.<br/>Command line: `docker pull bhaskarvk/rgeodataviz`

### Manually

If docker is not an option, then please install the following packages. Some of these packages have external dependencies, so be sure to consult individual package's documentation on installation procedures.

From CRAN install

-   Generic Packages
-   devtools
-   tidyverse
-   rmarkdown
-   shiny
-   roxygen2
-   rstudioapi
-   rsconnect
-   hrbrthemes
-   ggiraph
-   widgetframe
-   manipulateWidget
-   xaringan
-   knitr
-   Spatial Packages
-   sp
-   sf
-   regos
-   rgdal
-   raster
-   rasterVis
-   gdistance
-   geosphere
-   maps
-   maptools
-   gdalUtils
-   cleangeo
-   rmapshaper
-   spatstat
-   leaflet
-   leaflet.extras
-   leaflet.esri
-   leaflet.minimaps
-   ggmap
-   ggalt
-   ggspatial
-   rasterVis
-   lawn
-   geojson
-   geojsonio
-   geoaxe
-   geonames
-   wkb
-   tmap
-   mapview
-   mapedit
-   cartography
-   ggmap
-   cartogram
-   raturalearth
-   choroplethr
-   choroplethsMaps
-   plotly
-   highcharter
-   tilegramsR
-   acs
-   tigris
-   tidycensus
-   usmap
-   osmdata
-   OpenSteeetMap
-   plotKML
-   googleway
-   plotGoogleMaps
-   rbokeh
-   RNetCDF
-   ncdf4
-   rnoaa
-   ropenaq
-   animation

We also need development versions of certain packages, which can be installed from github. FOr each package name below install it using `devtools::install_github(<package-repo-name>')`. The repository names are given below

-   tidyverse/ggplot2
-   edzer/sfr
-   hrbrmstr/ggalt
-   hrbrmstr/albersusa
-   hrbrmstr/hrbrthemes
-   rstudio/leaflet
-   rstudio/rmarkdown
-   rstudio/crosstalk
-   mtennekes/tmap
-   bhaskarvk/leaflet.extras
-   bhaskarvk/leaflet.esri
-   '<r-spatial/mapview@develop>'
-   r-spatial/mapedit
-   nowosad/spData
-   dkahle/ggmap
-   walkerke/tidycensus
-   hrecht/censusapi
-   ropenscilabs/rnaturalearthhires
-   ropensci/geoparser
-   arilamstein/choroplethrZip
-   oswaldosantos/ggsn
-   paleolimbot/ggspatial
-   dgrtwo/gganimate
-   riatelab/cartography
-   bhaskarvk/user2017.rgeodataviz
