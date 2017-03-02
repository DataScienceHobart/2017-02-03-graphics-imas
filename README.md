# 2017-02-03-graphics-imas

## Session on graphics and maps in R

[R set up](https://github.com/DataScienceHobart/2017-02-03-graphics-imas/blob/master/setup-R.md)

## The Good Stuff

mapview

leaflet

ggplot2

### Extra stuff

General resources

[GIS with R](https://pakillo.github.io/GISwithR/#1)

[Introduction to visualising spatial data in R by Robin Lovelace and James Cheshire ](https://cran.r-project.org/doc/contrib/intro-spatial-rl.pdf)

[Create Maps with R Graphics](https://www.nceas.ucsb.edu/scicomp/usecases/CreateMapsWithRGraphics)

## Books

* GGPLOT2 http://ggplot2.org/book/
* R GRAPHICS COOKBOOK: http://www.cookbook-r.com/Graphs/
* Applied Analysis R Spatial: http://www.asdar-book.org/
* Intro to R Spatial: https://books.google.com.au/books/about/An_Introduction_to_R_for_Spatial_Analysi.html?id=zsf-AwAAQBAJ&source=kp_cover&redir_esc=y&hl=en


## Questions

These are all open questions!  We can use this to collect resources, all work in progress. 

* How to get data on oceanographic features and make nice maps? 

https://github.com/DataScienceHobart/2017-02-03-graphics-imas/issues/3

* How to add ice edge to maps? 

https://github.com/DataScienceHobart/2017-02-03-graphics-imas/issues/1

### interactive session

* a short overview of graphics in R
* pointers to the very large range of options
* a short excursion on graphics tips and tricks (thanks Rowan!)
* group hug about problems, identify some examples to explore

### Illustrations

Exactly what we do will depend on the group hug session. 

* get some data sets together and make a few figures, discussing problems and solutions
* work through software carpentry, and adapt with discussions: http://swcarpentry.github.io/r-novice-gapminder/08-plot-ggplot2/
* work trhough Data Carpentry: http://www.datacarpentry.org/lessons/#geospatial-data-workshop

## Broad topics to touch on

### Reading in data

Shapefiles

```R
raster::shapefile("myfile.shp")
```
Rasters, grids, images. 

```R
raster::raster("myraster.tif")

raster::brick("myRGB.tif")

raster::brick("myMegaSplat.nc", varname = "Mega")

raster::stack(c("mydata1.nc", "mydata2.nc", "mydata3.nc"))
```

Packages with data. 

maptools, rworldmap, maps, orsifronts, 

Here I list packages we should also look at so we know what they have. 

* [oce](https://CRAN.R-project.org/package=oce)
* [marmap](https://CRAN.R-project.org/package=marmap)
* [oceanmap](https://CRAN.R-project.org/package=oceanmap)
* [OceanView](https://CRAN.R-project.org/package=OceanView)
* [orsifronts](https://CRAN.R-project.org/package=orsifronts)
* [ocedata](https://CRAN.R-project.org/package=ocedata)
* [RmarineHeatWaves](https://CRAN.R-project.org/package=RmarineHeatWaves)
* [elevatr](https://CRAN.R-project.org/package=elevatr)
* [mregions](https://CRAN.R-project.org/package=mregions)



### colours

https://github.com/Bart6114/artyfarty

viridis

RColorBrewer

colorspace

### mapping

leaflet

mapview

raster and rgdal

sf

### graphics paradigms

ggplot2

base, lattice, grid

ggvis and leaflet and plotly


