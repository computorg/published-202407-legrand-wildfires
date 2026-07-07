# Bayesian spatiotemporal modelling of wildfire occurrences and sizes for projections under climate change
Juliette Legrand, François Pimont, Jean-Luc Dupuy, Thomas Opitz
2024-07-12

### Citation

Juliette Legrand, François Pimont, Jean-Luc Dupuy and Thomas Opitz (July 2024). Bayesian spatiotemporal modelling of wildfire occurrences and sizes for projections under climate change. Computo.
<https://doi.org/10.57750/4y84-4t68>

### Badges

[![build and
publish](https://github.com/computorg/published-202407-legrand-wildfires/actions/workflows/build.yml/badge.svg)](https://github.com/computorg/published-202407-legrand-wildfires/actions/workflows/build.yml)
[![reviews](https://img.shields.io/badge/review-report-blue)](https://github.com/computorg/published-202407-legrand-wildfires/issues?q=is%3Aopen+is%3Aissue+label%3Areview)
[![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/computorg/published-202407-legrand-wildfires)](https://archive.softwareheritage.org/browse/origin/?origin_url=https://github.com/computorg/published-202407-legrand-wildfires)
[![DOI:10.57750/4y84-4t68](https://img.shields.io/badge/DOI-10.57750%2F4y84--4t68-034E79.svg)](https://doi.org/10.57750/4y84-4t68)
[![Creative Commons
License](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)

### Authors’ affiliations

- Juliette Legrand (Biostatistics and Spatial Processes, INRAE, Avignon, France)
- François Pimont (Ecologie des Forêts Méditerranéennes (URFM), INRAE, Avignon, France)
- [Jean-Luc Dupuy](https://biosp.mathnum.inrae.fr/homepage-thomas-opitz) (Ecologie des Forêts Méditerranéennes (URFM), INRAE, Avignon, France)
- [Thomas Opitz](https://biosp.mathnum.inrae.fr/homepage-thomas-opitz) (Biostatistics and Spatial Processes, INRAE, Avignon, France)

### Abstract

Appropriate spatiotemporal modelling of wildfire activity is crucial for
its prediction and risk management. Here, we focus on wildfire risk in
the Aquitaine region in the Southwest of France and its projection under
climate change. We study whether wildfire risk could further increase
under climate change in this specific region, which does not lie in the
historical core area of wildfires in Southeastern France, corresponding
to the Southwest. For this purpose, we consider a marked spatiotemporal
point process, a flexible model for occurrences and magnitudes of such
environmental risks, where the magnitudes are defined as the burnt
areas. The model is first calibrated using 14 years of past observation
data of wildfire occurrences and weather variables, and then applied for
projection of climate-change impacts using simulations of numerical
climate models until 2100 as new inputs. We work within the framework of
a spatiotemporal Bayesian hierarchical model, and we present the
workflow of its implementation for a large dataset at daily resolution
for 8km-pixels using the INLA-SPDE approach. The assessment of the
posterior distributions shows a satisfactory fit of the model for the
observation period. We stochastically simulate projections of future
wildfire activity by combining climate model output with posterior
simulations of model parameters. Depending on climate models,
spline-smoothed projections indicate low to moderate increase of
wildfire activity under climate change. The increase is weaker than in
the historical core area, which we attribute to different weather
conditions (oceanic versus Mediterranean). Besides providing a relevant
case study of environmental risk modelling, this paper is also intended
to provide a full workflow for implementing the Bayesian estimation of
marked log-Gaussian Cox processes using the R-INLA package of the R
statistical software.
