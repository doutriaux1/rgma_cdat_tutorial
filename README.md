# RGMA CDAT Tutorial

## Setting up

* log into cori and follow instructions [here](https://github.com/CDAT/jupyter-vcdat/wiki/Connecting#using-vcdat-at-nersc)
* log to jupyter-hub at: https://jupyter.nersc.gov/hub/login?next=%2Fhub%2Fhome
* Go to your `$HOME` directory: `cd $HOME`
* Create a symlink to Forrest Hoffman's downloaded data: `ln -s /global/cscratch1/sd/cmip6 cmip6_data`
* clone the git repo to get the examples and tutorials: `git clone git://github.com/doutriaux1/rgma_cdat_tutorial`
* Finding home! Go to the "Jupyterlab" file navigator (folder icon at top left, bellow "orange Jupyter" icon and above "github cat icon"), click on the "home" button of this navigator, then navigate back to your home folder via the `home` directory, follwoed by the `jovyan` directory. `jovyan` is the container's user but it is mounted onto (linked to) your NERSC `$HOME` directory.
* In the Jupyterlab navigator, go to home and look for the `rgma_cdat_tutorial` folder. This folder contains our notebooks for the CDAT tutorial.
