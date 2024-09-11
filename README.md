# Meso_acoustics
Examining the effects of the 2015-2016 marine heatwave on the vertical distribution of mesopelagic fishes in the CCE using EK60 acoustics data collected by the Rockfish Recruitment and Ecosystem Assessment Survey (NOAA, SWFSC)

This project was created by Ily Iglesias (iiglesia@ucsc.edu) to make R code available for our publication: 
Vertical distribution of mesopealgic fishes deepens during marine heatwave in the California Current
https://doi.org/10.1093/icesjms/fsae129


Data used in this analysis:
- Processed acoustics data is available publically on Dryad (DOI): doi:10.5061/dryad.hmgqnk9s0
- CTD data available publically via erddap at: https://oceanview.pfeg.noaa.gov/erddap/tabledap/FED_Rockfish_CTD.html
or at Dryad (DOI): doi:10.5061/dryad.hmgqnk9s0
- Satellite data available publically via erddap at: https://coastwatch.pfeg.noaa.gov/erddap/griddap/erdMH1kd4908day.html


This project includes code to :
- input, read/clean and calculate metrics from processed acoustics data (Read clean.Rmd)
- conduct a spatial autocorrelation analysis (Spatial autocorrelation.Rmd)
- regrid to spatially independent grid cell size (Regrid.Rmd)
- compare acoustic backscatter and center of mass depth between years (Analysis 1.Rmd)
- extract CTD oceanographic data (Ocean data.Rmd)
- regrid ocean data to match gridded acoustic output (Ocean regrid.Rmd)
- extract satellite light data and add to gridded ocean data (satellite.Rmd)
- build a generalized additive model to explore the effect of ocean conditions on center of mass depth (Analysis 2 GAM.Rmd)
- plot oceanographic differences between years (Analysis 2 plots.Rmd)

Thus, we recommend the following steps for running these code in the following order:
- Read the publication available open acess at https://doi.org/10.1093/icesjms/fsae129
- Download data form Dryad (DOI): doi:10.5061/dryad.hmgqnk9s0 (and store these data in working directory as suggested in code)
- Run scripts in following order (Read clean --> Spatial autocorrelation --> Regrid --> Analysis 1 --> Ocean data --> Ocean Regrid --> satellite --> Analysis 2 GAM--> Analysis 2 plots)

Thank you for your interest in our study!
