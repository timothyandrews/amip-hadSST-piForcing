# amip-piForcing and hadSST-piForcing datasets

This repository contains the supporting global-annual-ensemble-mean dT and dN fluxes from `amip-piForcing`, `hadSST-piForcing` and `abrupt-4xCO2` simulations used and described in Andrews et al. (submitted).

Tim Andrews

Met Office Hadley Centre.

February 2022.

* Updated 1st July 2022:
	- Included data from CESM2 `hadSST-piForcing` simulation.
	- Corrected bug in `hadSST-piForcing` filenames (hadisst-piForcing -> hadSST-piForcing).
* Updated 4th July 2022:
	- Updated ESSOAR link from submitted to revised manuscript.

## Experiment descriptions

### amip-piForcing

`amip-piForcing` refers to an AGCM simulation forced with time-varying observed monthly SSTs and sea-ice using the AMIP II boundary condition SST and sea-ice dataset, forcing agents such greenhouse gases, aerosol emission etc. are kept at pre-industrial levels.

### hadSST-piForcing

`hadSST-piForcing` is identical to `amip-piForcing` in all aspects except SST boundary conditions are taken from HadISST1 (sea-ice remains the same as `amip-piForcing`)

### abrupt-4xCO2

`abrupt-4xCO2` simulations with each AGCMs parent AOGCM.

## Data description

All data are global-annual-ensemble-mean dT and dN timeseries. Ensemble size and time-periods covered for each experiment and AGCM is indicated in the table below.

| AGCM | Model description | amip-piForcing | amip-piForcing | hadSST-piForcing | hadSST-piForcing |
| --- | --- | --- | --- | --- | --- |
| | | Ensemble size | Time-period covered | Ensemble size | Time-period covered |
| CAM4 | Neale et al. (2013) | 3 | 1870 – 2014 | 3 | 1870 – 2014 |
| CESM2 | Danabasoglu et al. (2020) | 1 | 1870 – 2014 | 1 | 1870 – 2015 |
| CNRM-CM6-1 | Voldoire et al. (2019) | 1 | 1870 – 2014 | - | - |
| CanESM5 | Swart et al. (2019) | 3 | 1870 – 2014 |	- | - |
| ECHAM6.3 | Mauritsen et al. (2019) | 5 | 1871 – 2010 | 5 | 1871 – 2015 |
| GFDL-AM3 | Donner et al. (2011) | 1 | 1870 – 2014 | 1 | 1870 – 2014 |
| GFDL-AM4 | Held et al. (2019) | 1 | 1870 – 2016 | 1 | 1870 – 2016 |
| HadAM3 | Pope et al. (2000) | 4 | 1871 – 2012 | 4 | 1871 – 2012 |
| HadGEM2 | Martin et al. (2011) | 4 | 1871 – 2012	 | 1 | 1871 – 2012 |
| HadGEM3-GC31-LL | Williams et al. (2017) | 1 | 1870 – 2014 | 1 | 1871 – 2016 |
| IPSL-CM6A-LR | Boucher et al. (2020) | 1 | 1870 – 2014 | - | - |
| MIROC6 | Tatebe et al. (2019) | 1 | 1870 – 2014 | - | - |
| MRI-ESM2-0 | Yukimoto et al. (2019), Kawai et al. (2019) | 1 | 1870 – 2014 | - | - |
| MPI-ESM1-2-LR | Mauritsen et al. (2019) |	3  | 1871 – 2017 | 3 | 1871 – 2017 |


## Data files

See netCDF files in `data` directory.

## Citation and Use

Andrews, T, J.M. Gregory, Y. Dong, K. Armour, D. Paynter, P. Lin, A. Modak, T. Mauritsen, J. Cole, B. Medeiros, J. Benedict, H. Douville, R. Roehrig, T. Koshiro, H. Kawai, T. Ogura, J.-L. Dufresne, A. Bodas-Salcedo, R.P. Allan and C. Liu: [On the effect of historical SST patterns on radiative feedback](https://www.essoar.org/doi/10.1002/essoar.10510623.3). Submitted to Journal of Geophysical Research.

v1.0: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6799004.svg)](https://doi.org/10.5281/zenodo.6799004)

Please contact the author (timothy.andrews@metoffice.gov.uk) before using the data.
