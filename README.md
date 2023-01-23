#### Code and data repository for:

####  "Synoptic variability in satellite altimeter-derived radar freeboard of Arctic sea ice" - Nab et al. (2023), Geophysical Research Letters

### Data

The daily-resolution interpolated freeboard data can be found at: https://doi.org/10.5281/zenodo.6401726

The auxiliary data used can found at: 

- ERA5 snowfall, air temperature and wind speed: https://doi.org/10.24381/cds.adbb2d47

- SM-LG snow depth: https://doi.org/10.5067/27A0P5M6LZBI

- Sea ice type: https://doi.org/10.24381/CDS.29C46D83

The notebooks used to pre-process and regrid these data can be found in /auxiliary

### Notebooks

The notebooks used to produce the paper's main and supplementary figures can be found in /main_figs and /supp_figs respectively, and are named according to figure number. 

For the analysis, the freeboard and auxiliary data are each loaded into a 4018-day NETCDF, ranging from 01/01/2010-31/12/2020, with NaNs on days where there is no data

