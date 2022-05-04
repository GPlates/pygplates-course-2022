# PyGPlates course 2022

Join Dr. Ben Mather and Dr. Nicky Wright in an epic whirlwind tour of pyGPlates.

This repository contains jupyter notebooks showcasing some of the ways in which you can use `pygplates`. It accompanies the 2022 GPlates and pyGPlates workshop.

## Notebooks

1. Quick intro to Python and Jupyter
2. Getting started with PyGPlates: reconstructing points and coastlines
3. Motion paths and flowlines
4. Spreading and subduction rates
5. Reconstructing larger datasets
6. Velocities and an animation

## Documentation

PyGPlates documentation can be found [here](https://www.gplates.org/docs/pygplates/index.html).

More `pygplates` notebooks can be found [here](https://github.com/GPlates/pygplates-tutorials).

## Installation

The course will be held entirely online in the browser using the [edstem](http://edstem.org) platform, so no installation is necessary. However, if you wish to install pyGPlates on your own machine after the course then here are some instructions.

1. Download and install the latest [pygplates version](https://www.earthbyte.org/download-pygplates-0-36/) corresponding to your system architecture and operating system (Windows, Mac OS (Intel and ARM), Ubuntu are all supported) and take note of the installation directory and python path.
2. Install conda (we recommend [miniforge](https://github.com/conda-forge/miniforge)) and create a new environment e.g. `conda create -n pygplates python=3.9`.
3. Activate your new python environment with `conda activate pygplates`
4. Install the following dependencies: `conda install numpy scipy netcdf4 geopandas pandas cartopy jupyter rasterio conda-build`
5. Link to your pygplates installation using the python path you wrote down at step 1. In my case `conda develop /Users/ben/Downloads/pygplates_0.35.0_py39_Darwin-arm64`
6. Install some additional dependencies: `pip install PlateTectonicTools`.

Now you should have a working pyGPlates installation with additional dependencies required to run this course! Additional details on installing `pyGPlates` can be found [here](https://www.gplates.org/docs/pygplates/pygplates_getting_started.html#installing-pygplates). A conda package for pyGPlates is being developed.
