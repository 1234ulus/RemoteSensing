# RemoteSensing
Resources to run remote sensing analysis of ocean color products.
As an oceanographer, I have observed a large discrepancy between information on water and land remote sensing applications.
I share my notebooks to support other beginners in this field. 
I believe that working on these resources will help me systematize my own knowledge and recreate my analyses after a break.
Created notebook are base on NASA resources: https://oceancolor.gsfc.nasa.gov/resources/docs/tutorials/

By far I solved two main problems from this resorces:
1) How to deal with ValueError: "x and y arguments to pcolormesh cannot have non-finite values or be of type numpy.ma.MaskedArray with masked values" when want to plot coordninates on map
2) Add to plot with PACE data, band wavelangth information instead of an arbitrary discrete group

Python environment is needed, to run notebooks. 
1) I started with installing environment provided by NASA in file environment.yml How to do so fallow link below:
https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file
2) There is major crash in one main of packages*. Notebook can't import it. Solution is to uninstall it and install again by "PIP install".
3) I installed additional packages when there was a need
*I don't remember the exact name now. Soon I will be building the environment again so I will give the details then

My goal is to create for each interesting me satellite: MODIS, SENTINEL-3, PACE set of 3 jupyter notebook about:
searching and downloading, exploring, ploting.
