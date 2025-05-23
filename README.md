# 21CW Oceans Team Collaborative Research Project

Research Topic: We want to work together on obs vs model evaluation of air-sea interactions near the Southern Ocean Time Series ([SOTS](https://www.csiro.au/en/about/facilities-collections/mnf/voyages-schedules/multi-voyage-projects/sots-facility)) mooring . 

## Goal 1: Present poster at 21CW workshop in November 2025. 

Steps: 
* understand/evaluate the SOTS mooring data. The mooring data is at roughly 46.7S, 142E and spans 2010->. See [issue](https://github.com/PaulSpence/21CW_SOTS_Ocean/issues/14)
* evaluate ACCESS-om2 configs in the SOTS region (e.g. air-sea fluxes, T,S,O, atm fields) See [issue](https://github.com/PaulSpence/21CW_SOTS_Ocean/issues/15) 
* gather obs data in common directory on /g/data/jk72. See [issue](https://github.com/PaulSpence/21CW_SOTS_Ocean/issues/16)
* run a regional nested model of SOTS region at submesoscale resolution (~1km to 300 m). See [issue](https://github.com/PaulSpence/21CW_SOTS_Ocean/issues/9)

# How it works

All aspects of the project are tracked through [issues](https://github.com/PaulSpence/21CW_SOTS_Ocean/issues). Create an issue to represent each small task. Issues will develop to include discussion of analysis methods and figures associated with each task. 

The [Project/analysis Overview](https://github.com/users/PaulSpence/projects/3/views/1) lists all the analysis tasks (as detailed in the issues) at various stages.

To start contributing to the code, make your own branch directly in this repository, edit away on your branch, and then submit pull requests between your branch and the master branch (or merge directly).

# Meeting schedule

Every second Monday 2:30-4:30 in the IMAS board room or [zoom](https://utas.zoom.us/j/2515841854). See meeting notes here:
https://github.com/PaulSpence/21CW_SOTS_Ocean/issues/7

# Where stuff lives

No data? No worries. Datasets we're using live here:

| Dataset | Directory                                   |
|---------------|-----------------------------------------------|
| ERA5 (atm. reanalysis)           |  `/g/data/rt52/era5/single-levels/reanalysis`   |
| GLORYS (ocean reanalysis)        |  `/g/data/jk72/mxr581/SOTS-project-data/glorys`     |
| SOTS ocean                       | tba        |
| SOFS atm/fluxes                  | `/g/data/jk72/mxr581/SOTS-project-data/sots/flux`        |
| RG ARGO                          | `/g/data/jk72/mxr581/SOTS-project-data/RG_ARGO`        |

# Area of interest

- Proposed 3km model domain: `latitude_extent = [-55, -30], longitude_extent = [131, 158]`
- Proposed 1km model domain: maybe same? as compute permits!

Based on spatial plots of surface heat flux (?) or some other variable (?) we'd like to define a box over which we'll average key variables for timeseries plots



