# RemoteSensing

This repository include Jupyter notebook for ocean color and sea ice remote sensing products. As an oceanographer, I’ve observed a significant gap in accessible resources and tutorials focused on ocean applications of remote sensing, compared to terrestrial studies. This collection of Jupyter notebooks can support beginners and practitioners alike in exploring, analyzing, and interpreting oceanographic satellite data.



## Ocean color

I developed a Jupyter notebook focused on ocean color remote sensing using NASA’s official resources and tutorials available here:

https://oceancolor.gsfc.nasa.gov/resources/docs/tutorials/



So far, I’ve addressed two key challenges:



Resolving the ValueError: "x and y arguments to pcolormesh cannot have non-finite values or be of type numpy.ma. MaskedArray with masked values" error that occurs when plotting coordinates on a map.



Enhancing plots of PACE mission data by incorporating band wavelength information, rather than relying on arbitrary discrete groupings, to improve interpretability.



I have created notebooks:

1. MODISA\_download.ipynb for MODIS Aqua data searching, downloading data and basic visualization
2. PACE\_download.ipynb for PACE data searching, downloading data and basic visualization
3. PACE\_explore\_data.ipynb for PACE data level 1 and level 2, gruops, variables, bands visualization, blue, green red band



I have added graphs for SNAP data processing to obtain GeoTiffs.

1\. MODIS.xml , for MODIS data, level 2, OC product

2\. VII.xml , for VIIRS data, level 2, OC product

3\. SEN3.xml, for Sentinel - 3 data, level 2, WFR pruduct



## Sea Ice



Will be updated soon





## How to starts

To run these notebooks, you will need a working Python environment with the necessary scientific and geospatial libraries installed. It’s common to encounter package version conflicts or compatibility issues during updates. Different libraries may depend on specific versions of dependencies, which can sometimes cause errors or unexpected behavior.



It’s a good practice to start with a Python environment created from a reliable source: NASA, EUMETSAT

During your work, you may need to install additional packages or occasionally downgrade some to maintain compatibility.



Eumetsat enviroment: https://gitlab.eumetsat.int/eumetlab/oceans/ocean-training/sensors/learn-olci

