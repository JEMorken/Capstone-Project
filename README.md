# Capstone-Project
Spatial Analysis of Chicago Crime Data

## Overview
This is my Capstone Project for Springboard's course, Foundations of Data Science.  The project results are for a fictitious “client” (the Chicago Police) requesting analytic support for infrastructure investment decisions.  The purpose of the analysis was to determine significant spatial, temporal, and demographic crime patterns that could be used to guide infrastructure investments and/or improve policing patterns. I examined Chicago Crime Data from several angles and utilized multiple visual methods including the following:
- Histograms; Frequency of crime by type relative to
  o Police presence [proximity to PD’s]
  o Proximity to Transit stations, 
  o Hours of the day
  o Days of the week,
  o Community
- Choropleth maps showing crime density by community and select demographics
- Point analysis for the city as a whole that will include spatial standard deviation ellipses.
- Crime heat-maps
- Scatterplots and linear model analysis to determine the efficacy of a basic linear model in predicting crime density. 

My initial, spatial hypothesis was as follows:

1. Crime rates (as measured by count/km^2) decrease as one moves closer to a police department.
  o This assumes that proximity equates to higher police presence which acts as a deterrent.
  o Alternatively, police may be more likely to make an arrest for a crime where they most regularly patrol.
2. Crime rates increase as one moves closer to a transit station.

## Exploration Process

After setting up the superset of data, I started by exploring any relationships between daily/monthly crime rates [initially defined as count/community population] by sub-category and the following:
-	Various Demographics
-	Location Descriptions
-	Weather [temperature and precipitation]
-	Proximity Metrics
-	Temporal Charateristics

I also considered building a predictive model, but I found that my story line was getting spread too thin, so I ended up focusing on crime’s spatial characteristics.  Also, assuming that communities might have an outsized political effect on enacting any proposed solution, I framed the final story by community crime density defined as count/km^2, dropped the weather analysis, and refined the demographics down to a few key stats.  

In all, this was a very instructive exercise in working with geo-spatial data.  Thanks to a lot of time spent exporing the data, I learned a great deal about spatial visualization methods and regression models (both linear and non-linear).  I hope you enjoy the "final" product.

P.S. I say "final" b/c I hope to continue working on this topic in other projects of my own.  Check back for more later.
