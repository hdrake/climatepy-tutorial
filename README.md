
# climatepy-tutorial
Some tutorials for quickly learning python conventions and how to use libraries like netCDF4, numpy, and matplotlib to load, analyze, and plot climate data.

### A tutorial for python beginners
climate_data_tutorial.ipynb 
This file contains a Jupyter Notebook, a user-friendly interface for the programming language Python version 3. This notebook contains instructions for loading, analyzing, and plotting climate data saved in the common netCDF4 data format. If this is your first time using Python 3+ or Jupyter Notebooks, I recommend installing both via Anaconda (conda for short), software that lets you create independent programming environments with interdependencies in the programming libraries all figured out for you behind the scenes. The following two conda commands will install Python, Jupyter Notebook, and the three key python libraries we will use and activate the conda enviroment:

conda create -n climatepy-tutorial jupyter numpy matplotlib netcdf4
source activate climatepy-tutorial

### An exercise to test what you learned in the tutorials
global_average_exercise.ipynb

### A data set containing surface air temperatures for the years 2008-2017 from the Berkeley Earth team.
OBS_BerkeleyEarth_2008-2017.nc 
This netCDF4-formatted file contains global maps of monthly Surface Air Tempereature records for the years 2008-2017 compiled directly from weather station observations by the Berkeley Earth project.
