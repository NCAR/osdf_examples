# OSDF_Examples

## About
Contains Jupyter notebook workflows which access climate data from various [OSDF](https://osg-htc.org/services/osdf.html) origins using [PelicanFS](https://github.com/PelicanPlatform/pelicanfs). The examples include workflows where computations are executed on various platforms like NCAR's Casper, TACC's Stampede3 and cloud computing platforms like Jetstream2. 


## Example Workflows
1) Access CESM2 LENS data from the AWS opendata origin and the NCAR data origin and
   - a) [Bias-correct](jupyter_notebooks/cesm_bias.ipynb) surface temperature using ERA5 reanalysis. 
   - b) [Compute](jupyter_notebooks/cesm_oceanheat.ipynb) surface ocean heat content. 
2) Access NOAA SONAR data from the AWS origin to [plot echograms](jupyter_notebooks/sonar_ai.ipynb)
3) Run temperature bias-correction workflow on
   - a) [Stampede3](jupyter_notebooks/cesm_osdf_stampede3.ipynb)
   - b) [NCAR's Casper](jupyter_notebooks/cesm_posix_bias.ipynb)
4) [Compute](jupyter_notebooks/geocat_climatology.ipynb) climatological average of daily temperature data using [geocat-comp](https://geocat-comp.readthedocs.io/en/stable/examples/climatology_average.html) package
 

