# CurvyLapseRate
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3239539.svg)](https://doi.org/10.5281/zenodo.3239539)

Click here to launch interactive Notebooks
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nooksack-indian-tribe/CurvyLapseRate/master)

Code for processing sub-daily temperature sensor data for analysis of elevation distributed micro-climatology processes in a coastal glaciated watershed.  Code allows for visualization and publication of daily data in multiple formats (1) daily data in python dictionaries for analysis (2) daily data for visualization and download on HydroServer at data.cuahsi.org (ODM format), and (3) archive publication on the HydroShare repository (ODM2 format)).

Air temperature and relative humidity were collected on a longitudinal transect in the North Fork Nooksack River Watershed in Whatcom County, Washington using methods described in (Hubbart et al., 2005; Lundquist & Cayan, 2007; Lundquist & Lott, 2008). This code is useful for assessment of observations, especially lapse rates with increasing elevation and microclimatic influences.  Every hydrologic model that we know of (circa 2019) uses a linear annual lapse rate (e.g. -6.5 C/km clear sky assumption; - 4.5 C/km North Cascades Mountain Range (Minder et al., 2010) to represent the change in temperature with elevation.  We are collecting empirical evidence to test the hypothesis that high elevation temperature lapse rates in glaciated mountain peaks, especially in maritime climates, are linear.  They may be curvy.

Preliminary data analysis from the North Fork Nooksack (northern flank of Mt. Baker) shows a consistent annual average (-4.4 C/km) to previous work (Minder et al., 2010).  However, at the lowest elevations (~664m -1056m) the annual average lapse rate is ~ 2.3 C/km; at mid elevations (1056m- 1575m) the annual average lapse rate is ~ 5.4 C/km; at higher elevations (1575m-1743m) the annual average lapse rate is ~ -7.2 C/km.  If mountain lapse rates are significantly different from modeled rates, this is expected to have significant implications for high elevation snow, glacier, and hydrologic model predictions.  

Curvy is something to be proud of.     -Paloma Faith

### Citation suggestions: 

**Data Publication:**
Bandaragoda, C., J. Beaulieu, N. Cristea, C. Beveridge,  (2019). elevation distributed micro-climatology data in a coastal glaciated watershed, Data in Brief, (in preparation). 

**Data Resource:**
J. Beaulieu, Bandaragoda, C., C. Beveridge, N. Cristea (2019). Nooksack Temperature Lapse Rate Study, HydroShare, http://www.hydroshare.org/resource/2d9787bf36d04c9383e595d179f9298b

**Code:**
C. Beveridge, N. Cristea, Bandaragoda, C., J. Beaulieu. (2019, June 5). nooksack-indian-tribe/CurvyLapseRate: Alpha release to create DOI for Nooksack Indian Tribe (Version v0.0.1-alpha). Zenodo. http://doi.org/10.5281/zenodo.3239539

**Land Acknowledgement:**
The Coast Salish people are the indigenous inhabitants of Western Washington. The Nooksack Watershed, from the peak of Mount Baker to the Bellingham Bay, is the unceded ancestral land of the Nooksack Tribe and Lummi Nation. They are still here, continuing to honor and bring to light their ancient heritage. The University of Washington acknowledges the Coast Salish peoples of this land, the land which touches the shared waters of all tribes and bands within the Suquamish, Tulalip and Muckleshoot nations.

### References: 

[1]
J.D. Lundquist, F. Lott
Using inexpensive temperature sensors to monitor the duration and heterogeneity of snow-covered areas
Water Resour. Res., 44 (2008), 10.1029/2008WR007035
W00D16
Google Scholar

[2]
P.H. Stone, J.H. Carlson
Atmospheric lapse rate regimes and their parameterization
J. Atmos. Sci., 36 (3) (1979), pp. 415-423
CrossRefView Record in ScopusGoogle Scholar

[3]
J.R. Minder, P.W. Mote, J.D. Lundquist
Surface temperature lapse rates over complex terrains: lessons from the Cascade mountains
J. Geophys. Res., 115 (2010), p. D14122, 10.1029/2009JD013493
Google Scholar

[4]
A.F. Hamlet, P.W. Mote, M.P. Clark, D.P. Lettenmaier
Effects of temperature and precipitation variability on snowpack trends in the western United States
J. Clim., 18 (21) (2005), pp. 4545-4561
View Record in ScopusGoogle Scholar
[5]
P.W. Mote, S. Li, D.P. Lettenmaier, M. Xiao, R. Engel
Dramatic declines in snowpack in the western US
Npj Clim. Atmos. Sci., 1 (1) (2018), p. 2
Google Scholar

[6]
C. Frans, E. Istanbulluoglu, D.P. Lettenmaier, A.G. Fountain, J. Riedel
Glacier recession and the response of summer streamflow in the Pacific Northwest United States, 1960–2099
Water Resour. Res., 54 (2018), pp. 6202-6225, 10.1029/2017WR021764
CrossRefView Record in ScopusGoogle Scholar

[7]
E.P. Maurer, L. Brekke, T. Pruitt, P.B. Duffy
Fine‐resolution climate projections enhance regional climate change impact studies
Eos Trans. Am. Geophys. Union, 88 (47) (2007), p. 504
504
CrossRefView Record in ScopusGoogle Scholar

[8]
E.P. Salathé Jr., A.F. Hamlet, C.F. Mass, S.Y. Lee, M. Stumbaugh, R. Steed
Estimates of twenty-first-century flood risk in the Pacific Northwest based on regional climate model simulations
J. Hydrometeorol., 15 (5) (2014), pp. 1881-1899
View Record in ScopusGoogle Scholar

[9]
B. Livneh, T.J. Bohn, D.W. Pierce, F. Munoz-Arriola, B. Nijssen, R. Vose, L. Brekke
A spatially comprehensive, hydrometeorological data set for Mexico, the US, and Southern Canada 1950–2013
Sci. Data, 2 (2015), Article 150042
View Record in ScopusGoogle Scholar

[10]
B. Henn, M.S. Raleigh, A. Fisher, J.D. Lundquist
A comparison of methods for filling gaps in hourly near-surface air temperature data
J. Hydrometeorol., 14 (3) (2013), pp. 929-945
View Record in ScopusGoogle Scholar

[11]
S. Manabe, R.F. Strickler
Thermal Equilibrium of the Atmosphere with a Convective Adjustment
J. Atmos. Sci., 21 (1964), pp. 361-385, 10.1175/1520-0469
CrossRefView Record in ScopusGoogle Scholar

