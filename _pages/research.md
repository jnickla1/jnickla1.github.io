---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

I have a diverse array of many different research projects, some of which I am actively working on, others I plan to revisit at a later time. Here I list them in order of current importance.

# Environmental Exposures and Health Risks
I aim to connect health outcomes to recent & future climate change.


## Bayesian Modeling of Climate Dependent Mortality Risk among US Residents from 1989 to 2020.
I am working with Erin Kim (an undergraduate freshman), [Prof. Baylor Fox-Kemper (DEEPS)](https://vivo.brown.edu/display/bfoxkemp), [Prof. Charles Lawrence (APMA, emeritus)](https://vivo.brown.edu/display/clawrenc), and [Dr. Katelyn Moretti (Brown Emergency Medicine)](https://watson.brown.edu/chrhs/people/katelyn-moretti). We aim to identify individuals who are most at risk from extreme heat exposure, to eventally give physicans the tools to protect them (such as alerting them with a call when a heat wave is apporaching, or adjusting their medications).

The overall analysis will involve two major steps: 1) Temperature mortality function determination, methodologically based on Distributed Lag Nonlinear Models from [Gasparrini 2010](https://doi.org/10.1002/sim.3940), and 2) Bayesian analysis of covariate (clinical diagnoses, demographical, and occupational) interactions using a technique called spike and slab from [George & McCulloch 1997](http://www.jstor.org/stable/24306083).

![MCOD Poster](/images/publications/ClimateMortality_MCOD_poster.png)

To perform this analysis, we are gathering datasets to examine statistical correlations. In January, 2023 we applied to the CDC-NCHS to access the Detailed Multiple Cause of Death Research Files ([MCOD](https://wonder.cdc.gov/wonder/help/mcd.html)). We will connect this database to large climate data reanalysis prodect, e.g., [ERA5-Land](https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-land?tab=overview). 



## 3CRS: Hospitalizations due to Extreme Temperature and Flooding in Rhode Island and Maine
 I’m also involved in the [Community Coastal Climate Research and Solutions (3CRS)](https://www.brown.edu/news/2023-08-07/coastal-resilience) project funded by an NSF grant involving a collaboration between Brown, the University of Rhode Island,  Rhode Island College, University of New Hampshire, Gulf of Maine Research Institute and Northeastern Regional Association of Coastal Ocean Observing Systems. My portion of this project (in collaboration with [Dr. Katelyn Moretti](https://watson.brown.edu/chrhs/people/katelyn-moretti), [Dr. Elizabeth Fussell](https://www.brown.edu/academics/population-studies/people/person/elizabeth-fussell), and [Dr. Albert Larson](https://vivo.brown.edu/display/alarso19)) will examine both heat waves and flooding events in New England and how these can impact health care systems.
<br>
Rates of health outcomes such as ICD-10 diagnoses, ED visits, and need for hospitalizations will be quantified for the specific communities relative to the four communities of interest in the 3CRS proejct: the Port of Galilee (RI), the Port of Providence (RI), Bath (ME), and Rockland (ME). Seasonal, annual, day-of-the-week, and specific disease-related variations will be fit across many years, and this expected baseline will be removed from the rates of health outcomes attributable to environmental insults. By collecting many such attributable environmental health outcomes at the census block level, a generalized linear regression model (GLM) will be fit to predict the magnitude of these outcomes.

## Interaction of Air Pollution and Extreme Temperature: Machine Learning Estimation
Environmental exposures, both to air pollution and temperature extremes, cause significant injury and mortality.  Doctors, public servants, and individual citizens can better protect those at risk if they can estimate and predict that environmental risk. Physiological and behavioral mechanisms underpin a potential interaction between these exposures: high temperatures make the same level of air pollution more dangerous. While several prior population studies have quantified this interaction, they are potentially biased by inaccurate and sparse measurements of air quality. This project proposes to 1) combine multiple existing machine learning models to estimate local air pollution, 2) precisely quantify the interaction between air pollution and temperature on mortality, and 3) use this improved risk model to project future environmental mortality. 
![ML toy model](/images/publications/GoogleResearchProposal.png)

## Post-Discharge Time-Varying Hazard Environmental Exposures
I aim to extend [Gasparrini's](https://doi.org/10.1002/sim.3940) Distributed Lag Nonlinear Model to account for a [time-varying hazard](http://dx.doi.org/10.21037/atm.2018.02.12) in a post-discharge patient setting. This work is in collaboration with a former fellow medical student, [Dr. Allison Navarrete-Welton]( https://www.researchgate.net/profile/Allison-Navarrete-Welton), who is interested in the risk from extreme heat for patients that just underwent cardiovascular surgery. In this statistical problem, there are two temporal variables that are both important: the followup time since a patient was discharged home, and the lag time that has passed since a patient was potentially exposed to an extreme temperature event. We expect that both heat exposures that happened immediately after a patient was discharged (and thus most vulnerable), and those heat exposures in the most recent past to have the greatest effect on a patient's current risk for readmission.



# Ocean Geoengineering
During my first year of undergrad at Brown, I began a quest to reseach a geoengineering idea: what if we could grow an algae that could lower our planet’s fever by reflecting light away in the oceans. This would be a potential alternative to trying to put dust in the stratosphere (stratospheric solar radiation management, or SRM). Just slowing the rate of change might be helpful for adaptation and preventing species from going extinct.
![GeoengSchematic](/images/publications/GeoengPres.png)
Testing this idea involves a computer simulation of many processes using additional code inserted into [NCAR's CESM](https://www.cesm.ucar.edu/): reflection of light on the ocean surface, absorption, bouyancy, decay of reflective particles, and light shielding onto the ocean ecosystem below. This will be a significant expansion on a prior G4Foam experiment by [Gabriel et. al. in 2017](https://acp.copernicus.org/articles/17/595/2017/).


# Kalman Filtered Climate State
The global average of the Earth's historical climate over the past 150 years can be explained by a thermal/radiation physics equation involving a small number of constants (17), atmospheric CO2 concentration, human-produced cloud-seeding aerosols, and dust from volcanic eruptions. Global mean surface temperature measurements vary around this climate state within a consistent normal distribution. This physics equation and statistical depiction allowed us to construct a simple model that can rapidly estimate the uncertainty in Earth’s current climate, aid in policy discussions, and reduce ensemble modeling costs. 


<img src="/images/publications/EBM_Schematic_v4.png" width="50%">
<img src="/images/publications/extendKalmanFilter.png" width="40%">
<br> <br>
This work is in the last phase of peer review for the Journal of Climate, and a preprint can be found [here](https://doi.org/10.31223/X5FH2C). It will soon contribute to a collaboration paper with [Dr. Peter Thorne](https://www.maynoothuniversity.ie/faculty-social-sciences/our-people/peter-thorne) regarding "How will we know we have reached 1.5°C".

# Venous Thrombosis and Clinical Cardiology

I have spent my two summers in undergrad working for Dr. Peter Henke in the [Jobst Vascular Lab at the University of Michigan](https://medicine.umich.edu/dept/surgery-research/research-strengths/vascular-biology/conrad-jobst-vascular-research-laboratories/henke-lab), the first as a [Frankel Summer Research Fellow](https://sites.google.com/site/cvcsummerfellowship/home) primarily performing empirical histology stains on thrombus tissue, and the second  as a research assistant continuing research on mouse models of deep vein thrombosis. In addition, because of my background in mathematics and statistics, Dr. Henke gave me the opportunity to analyze and report clinical data from the Carotid Artery Revascularization Consortium of Southeastern Michigan, presented at the [2019 Academic Surgical Congress](https://www.asc-abstracts.org/abs2019/81-07-transfemoral-carotid-artery-stenting-is-inferior-to-carotid-endarterectomy-in-the-community/). I have also been involved in a number of similar projects in clinical cardiology, ranging from diuretic use to left bundle branch block to restenosis of stented veins. Astracts for some of these projects were accepted at the [2018 American Heart Association Scientific Sessions](https://www.ahajournals.org/doi/10.1161/circ.138.suppl_1.16500) and the [2020 American College of Cardiology](https://www.jacc.org/doi/abs/10.1016/s0735-1097%2820%2931586-2) conference.

# Vertical Axis Wind Turbine
In high school I won the Engineering Division of the Michigan State Science Fair with a physical miniature prototype  (now [patented](https://patents.google.com/patent/US9752557B2/en)) for a novel vertical axis wind turbine (or VWAT). My design is significantly more efficient than other VWATs, due to a mechanism of linking opposing sails/blades. VAWTs have traditionally been ignored in favor of horizontal-axis wind turbines (HAWTs) in most commercial wind farms due to the higher efficiency of HAWT designs that can be rotated to face the wind. However, on the open sea, rotating HAWTs are too unstable and wind are generally stronger and omnidirectional. These conditions are advantageous to VAWT, such as mine, which can capture wind from all directions. I currently hope to market my design to a larger manufacturing or research company, or construct/model a larger marine prototype.

<img src="/images/4bladeTurbine.png" width="45%">
<img src="/images/VWATship1.png" width="45%">
