---
title: "Urban Heat Island, Tree Cover, and Communities"
output: html_document
date: "2019-08-01T00:00:00Z"
tags:
- Water Resources
- Data Science
- Environmental Equity
- UHI
---

















Air temperatures in cities are substantially higher than in adjacent rural areas. In the United States, the average difference can be as much as 16°F for severely affected cities (Imoff et al. 2010). This phenomenon, known as urban heat island (UHI), results from differences in surface heat reflection and absorption. High levels of dark, impervious surfaces; lack of vegetation; and urban geometries increase absorption and decrease evapotranspiration. This leads to increases in temperature and thermal discomfort. Increased thermal discomfort can cause psychological stress, decrease productivity, and lead to death in vulnerable populations (Poumadere 2003, Kovats 2008, Kjellstrom 2009).

One cost effective way to mitigate UHI is through a mature tree canopy. However, trees are not evenly distributed in American cities. Census and tree canopy data around Austin, TX shows patterns in how trees are distributed by social factors. The figure below shows patterns between median household income and tree cover. Census tracts with higher income generally appear to have a higher tree cover. 





<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-7-1.png" width="672" /><img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-7-2.png" width="672" /><img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-7-3.png" width="672" />

This visual association is backed up by regressional analysis. There is a significant association between tree cover and median income for the Austin area (see figure below, *** indicates p<0.001).  






<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-11-1.png" width="672" />









In addition to an association with income, tree canopy cover also shows a relationship with race. 

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-15-1.png" width="672" /><img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-15-2.png" width="672" />



Like the relationship between income and trees, regressional analysis shows this is a statistically significant relationship (see figure below, *** indicates p<0.001).



<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-18-1.png" width="672" />

##Conclusions

Tree canopy is a cost effective way to mitigate the dangerous health and social impacts from urban heat island. However, tree cover shows uneven distribution in Austin, TX with race and income. Visualizations and statistical analysis both show an association with more tree cover in higher income, whiter areas. Regressional analysis only demonstrates the these factors are related not that these factors are directly causal. As a result, the associations shown above do not necessarily imply these census tracts were caused to be less or more tree covered due to racial or income demographics. However, this analysis does show tree cover is not evenly distributed by social class. Regardless of cause, lower income, nonwhite people in Austin are less likely to have tree cover than high income white neighborhoods. Unequal tree cover is an important environmental equity concern for Austin, TX and needs to be addressed in any city environmental plan. 

##References
Imhoff ML, Zhang P, Wolfe RE, Bounoua L. Remote sensing of the urban heat island effect across biomes in the continental USA. Remote Sens Environ. 2010;114(3):504-513. doi:10.1016/j.rse.2009.10.008

Karimipour N. Implications of Urban Design Strategies for Urban Heat Islands: An Investigation of the UHI Effect in Downtown Austin, Texas. 2017.

Kjellstrom T, Holmer I, Lemke B. Workplace heat stress, health and productivity – an increasing challenge for low and middle-income countries during climate change. Glob Health Action. 2009;2(1):2047. doi:10.3402/gha.v2i0.2047

Kovats RS, Hajat S. Heat Stress and Public Health: A Critical Review. Annu Rev Public Health. 2008;29(1):41-55. doi:10.1146/annurev.publhealth.29.020907.090843

Poumadere M, Mays C, Le Mer S, Blong R. The 2003 Heat Wave in France: Dangerous Climate Change Here and Now. Risk Anal Off Publ Soc Risk Anal. 2006;25:1483-1494. doi:10.1111/j.1539-6924.2005.00694.x

Richardson S. A GEOSPATIAL ANALYSIS OF THE URBAN HEAT ISLAND EFFECT IN AUSTIN, TX. May 2015.

Urban heat island data is based off of land surface temperature taken in 2014 (https://data.austintexas.gov/Locations-and-Maps/Tree-Planting-Prioritization-2014/psx7-v95h)

Tree canopy cover is based off a 2014 City of Austin raster dataset. Contact for further details. 

