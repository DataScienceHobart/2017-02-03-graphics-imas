# 2017-02-03-graphics-imas

## Session on graphics and maps in R

If you want to try R code while we discuss, recommend having `R 3.3.2` installed with packages `leaflet`, `sp`, `rgdal`, `tidyverse`, `maptools`, `rworldmap`, and `mapview` (all up to date). 

To install all these, you should need only to 

```R
install.packages(c("leaflet", "sp", "rgdal", "tidyverse", "maptools", "rworldmap", "mapview"))
```

but if you have problems, don't worry it's not critical. (But feel free to email the organizer/s. )

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


