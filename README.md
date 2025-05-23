# Data Component Use Case for Overland Flow Simulation
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/gantian127/overlandflow_usecase/blob/master/LICENSE.txt)

This repository includes a [Jupyter Notebook](overland_flow.ipynb) which demonstrates how to use 
the [CSDMS Data Component](https://csdms.colorado.edu/wiki/DataComponents) to download the topography dataset 
and use the [Landlab](https://landlab.readthedocs.io/en/master/) components 
to delineate the watershed and simulate the overland flow for a study area in the Boulder County.

This Jupyter Notebook is part of the work for a research paper
["CSDMS Data Components: data-model integration tools for Earth surface processes modeling"](https://gmd.copernicus.org/articles/17/2165/2024/gmd-17-2165-2024.html).

### Notebook Citation
Gan, T., Tucker, G. E., Overeem, I. (2024). Data Component Use Case for Overland Flow Simulation, HydroShare, 
https://doi.org/10.4211/hs.f94596fe50e74d93bd372125c5fab424


### Run the Notebook
You can choose the following methods to run this Jupyter Notebook: 

[//]: # (#### Method 1: HydroShare)

[//]: # (Please go to the [HydroShare Resource]&#40;https://www.hydroshare.org/resource/bcbcfe823cc4432f8ce96c3048d4591f/&#41; )

[//]: # (and follow the instruction in the **"Abstract"** section to run this notebook.)

#### Method 1: CSDMS JupyterHub
Please go to the [CSDMS EKT Lab](https://csdms.colorado.edu/wiki/Lab-0030) 
and follow the instruction in the **"Lab notes"** section to run this notebook.


#### Method 2: Local PC
Please first download all the files from this repository and have 
[conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) installed on the local PC.
Then, use the following commands to create a virtual environment and launch the Jupyter Notebook. 
The code below works best on Mac OS or Linux and may cause some errors on Windows.
```
$ cd overlandflow_usecase
$ conda env create --file=environment.yml
$ conda activate overlandflow_usecase
$ jupyter notebook
```
