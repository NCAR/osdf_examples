# OSDF_Examples

## About
Contains Jupyter notebook workflows which access climate data from various [OSDF](https://osg-htc.org/services/osdf.html) origins using [PelicanFS](https://github.com/PelicanPlatform/pelicanfs). The examples include workflows where computations are executed on various platforms like NCAR's Casper, TACC's Stampede3 and cloud computing platforms like Jetstream2. 


## Example Workflows
1) Access CESM2 LENS data from the AWS opendata origin and the NCAR data origin and
   - a) [Benchmark](notebooks/ndc_workflows/aws_benchmark.ipynb) data access speeds for subsets of various sizes.
   - b) [Bias-correct](notebooks/cesm_bias.ipynb) surface temperature using ERA5 reanalysis. 
   - c) [Compute](notebooks/cesm_oceanheat.ipynb) surface ocean heat content.
   - d) [Compute](notebooks/cesm_gmst_ncar.ipynb) GMST anomaly and plot.
2) Access NOAA SONAR data from the AWS origin to [plot echograms](notebooks/ndc_workflows/sonar_ai.ipynb)
3) Access NA-CORDEX data from NCAR's Research Data Archive and make some diagnostic [plots](notebooks/na_cordex.ipynb)
4) Benchmark data access speeds from the NCAR data [origin](notebooks/ndc_workflows/ncar_benchmark.ipynb) using the DART reanalysis dataset and make [diagnostic plots](notebooks/dart-cam6.ipynb)
5) Benchmark data access speeds from the NCAR's data [origin](notebooks/ndc_workflows/ncar_benchmark_ap40.ipynb), when the data is accessed from the OSPool's access point AP40
6) Run temperature bias-correction workflow on
   - a) [Stampede3](notebooks/cesm_osdf_stampede3.ipynb)
   - b) [NCAR's Casper](notebooks/cesm_posix_bias.ipynb)
7) [Compute](notebooks/geocat_climatology.ipynb) climatological average of daily temperature data using the [geocat-comp](https://geocat-comp.readthedocs.io/en/stable/examples/climatology_average.html) package
8) Access CMIP6 zarr data from (27 Global Climate Models) AWS and plot the evolution of [Global Mean Surface Temperature](notebooks/cmip6_aws_zarr.ipynb) with time. The model projections were also compared with the [HadCRUT5](https://www.metoffice.gov.uk/hadobs/hadcrut5/) observational dataset.

### Machine learning workflows
1) Use logistic regression to [predict](notebooks/ml_workflows/nino3.4_index.ipynb) Nino3.4 indices in advance. The training data are Sea Surface Temperature values and observed nino indices hosted on NCAR's RDA.
 

