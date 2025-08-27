# 3D_groningen
A python implementation to load and visualize 3D displacement vectors, including their error ellipses, over Groningen which were obtained from the strap-down decomposition over the province of Groningen. 

Reference: Brouwer, Wietske S., and Ramon F. Hanssen. "Estimating three-dimensional displacements with InSAR: the strapdown approach." Journal of Geodesy 98.12 (2024): 110. https://doi.org/10.1007/s00190-024-01918-2 

# Requirements

- numpy
- pandas
- matplotlib
- contextily
- geopandas
- pykrige

# Data
To generate the displacement vectord and inlcuding error ellipses you need the following dataset:

- A set of estiamted displacement parameters including 6 variance and covariance values
- Optionally: a shapefile of the Groningen reservoir

An example set of parameters is available through 4TU.ResearchData. Users can download the data and the metadata from that repository to plot the corresponsing displacement vectors using this repository. 
