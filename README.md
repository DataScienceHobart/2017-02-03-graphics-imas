# Graphics and maps in R


[R set up](https://github.com/DataScienceHobart/2017-02-03-graphics-imas/blob/master/setup-R.md)


## Getting Help

Local

* Data Science Hobart https://twitter.com/DataScienceHbt, https://datasciencehobart.github.io/  
* R Ladies Hobart https://twitter.com/hashtag/RLadiesHobart?src=hash
* Gentle R http://australianantarcticdatacentre.github.io/GentleR/About/
* HRUG Hobart R Users Group https://www.meetup.com/Hobart-R-Users-Group/


Worldwide

* [Twitter #rstats](https://twitter.com/search?q=rstats)
* [Stackoverflow #r topic](http://stackoverflow.com/questions/tagged/r)
* [Stackoverflow #ggplot2 topic](http://stackoverflow.com/questions/tagged/ggplot2)
* [Spatial StackExchange](http://gis.stackexchange.com/)
* [R spatial mailing list](https://stat.ethz.ch/mailman/listinfo/r-sig-geo)
* [R help mailing list](https://stat.ethz.ch/mailman/listinfo/r-help)

## The Good Stuff

* **ggplot2** http://swcarpentry.github.io/r-novice-gapminder/08-plot-ggplot2/

* **R leaflet**  https://rstudio.github.io/leaflet/

* **mapview** https://environmentalinformatics-marburg.github.io/mapview/introduction.html


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

### interactive session

http://pad.software-carpentry.org/DaSH-R

* overview of graphics in R  [The R Graphics Landscape](https://www.stat.ubc.ca/~jenny/STAT545A/block90_baseLatticeGgplot2.html)

* graphics tips and tricks 

http://rpubs.com/cyclemumner/aad-mapping-tips

* group session about problems, identify some examples to explore


## Questions

These are all open questions!  We can use this to collect resources, all work in progress. 

* How to get data on oceanographic features and make nice maps? 

https://github.com/DataScienceHobart/2017-02-03-graphics-imas/issues/3

* How to add ice edge to maps? 

https://github.com/DataScienceHobart/2017-02-03-graphics-imas/issues/1


### Illustrations

Exactly what we do will depend on the group session. 

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


