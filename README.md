# Meso_acoustics
Examining the effects of the 2014-2016 marine heatwave on mesopelagic fishes in the CCE

This project was created by Ily Iglesias to make R code available upon publication.

Data used in this analysis:
- Processed acoustics data is available publically on Dryad (DOI): doi:10.5061/dryad.hmgqnk9s0
- CTD data available publically via erddap at: https://oceanview.pfeg.noaa.gov/erddap/tabledap/FED_Rockfish_CTD.html
- Satellite data available publically via erddap at: https://coastwatch.pfeg.noaa.gov/erddap/griddap/erdMH1kd4908day.html


This project includes code to :
- input, read/clean and calculate metrics from processed acoustics data (Read clean.Rmd)
- conduct a spatial autocorrelation analysis (Spatial autocorrelation.Rmd)
- regrid to spatially independent grid cell size (Regrid.Rmd)
- compare acoustic backscatter and center of mass depth between years (Analysis 1.Rmd)
- extract CTD oceanographic data (Ocean data.Rmd)
- regrid ocean data (Ocean regrid.Rmd)
- extract satellite light data and add to gridded ocean data (satellite.Rmd)
- build a generalized additive model to explore the effect of ocean conditions on center of mass depth (Analysis 2.Rmd)
- plot oceanographic differences between years (Analysis 2 plots.Rmd)
