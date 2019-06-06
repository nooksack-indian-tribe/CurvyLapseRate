# CurvyLapseRate
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3239539.svg)](https://doi.org/10.5281/zenodo.3239539)

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

### References 

Hubbart, J., Link, T., Campbell, C., & Cobos, D. (2005). Evaluation of a low‐cost temperature measurement system for environmental applications. Hydrological Processes: An International Journal, 19(7), 1517-1523.

Lundquist, J. D., & Cayan, D. R. (2007). Surface temperature patterns in complex terrain: Daily variations and long‐term change in the central Sierra Nevada, California. Journal of Geophysical Research: Atmospheres, 112(D11).

Lundquist, J.D. and Lott, F. 2008. Using inexpensive temperature sensors to monitor the duration and heterogeneity of snow-covered areas.  Water Resour. Res., 44, W00D16, doi: 10.1029/2008WR007035. 

Minder, J.R., Mote, P.W., Lundquist, J.D. 2010. Surface temperature lapse rates over complex terrains: Lessons from the Cascade Mountains. J. Geophys. Res. 115, D14122, doi:10.1029/2009JD013493.
