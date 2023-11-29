# ET and Geophysics the perfect match?
Ideas to couple ET and Geophysics

## What can I find in this repo?

- Glossary
- References 
- Idea developement (projects redaction)

## Observations
### Earth Observations (EO)
- Quick overview of EO satelite data available and how to fetch/prepare them: [pyEO](pyEO.md)

### Proximal Sensing Observations (PS)

### Ground Observations (GB)

## Modelling

https://hess.copernicus.org/articles/19/2017/2015/hess-19-2017-2015.pdf

Therefore water-balance and energy-balance approaches are two of the main methodologies for modelling this process. The water-balance approach is usually implemented as a complex, distributed hydrological model, while the energybalance approach is often used with remotely sensed observations of, for example, the land surface temperature (LST) and the state of the vegetation.


### Water-balance 
### Energy-balance approaches


## Interaction and links between GB, PS and EO

- Geophysic to map land use precisely; 3TSEB but why not 4,5 or 6 including soil compaction, soil physics water capacity holding etc ...
- Improve FAO-56 model

    ETc, adj = ETo (Ke + KcbKs)

    - ETc, adj [L/T] is the adjusted crop ET for non-optimal conditions
    - ET o [L/T] is the reference ET of a well-watered grass surface
    - Ke [-] is the soil evaporation coefficient
    - Kcb [-] is the basal crop coefficient (for transpiration)
    - Ks [-] is the water stress coefficient (for transpiration)

    Calculating Kr and Ks as a function of SWC instead on cumulative depletion of soil water (approach FAO). This SWC-based approach doesn’t require temporal fluxes as inputs, and it allows spatial analysis of soil water stress when spatial SWC characterization is available.
