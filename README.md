# Renaissance Simulation Starter

*A starter toolkit for exploring halo data from the Renaissance Simulations.*


## Run Online

[Run in Binder](https://mybinder.org/v2/gh/emilytroutman0/renaissance_starter/main)

Launch the notebooks directly in your browser.


## Website and Full Instructions

https://www.firstgalaxies.physics.gatech.edu

The website includes:

- Information about the data  
- Instructions for downloading large datasets (Globus and browser)  
- Background on the Renaissance simulations  


## Repository Contents

**Notebooks**

- `halo_starter_script.ipynb`  
  Explore a *single halo file*

- `region_simple_starter_script.ipynb`  
  Work with *full region HDF5 files*

- `region_detailed_starter_script.ipynb`  
  More advanced exploration  

**Data**

- `practice_halo_catalog.hdf5`  
  Small practice dataset  

- `void_halo_0.hdf5`  
  Example single halo file  


## Data Overview

### Single Halo Files
- Small and easy to work with  
- Example: `void_halo_0.hdf5`  
- Used in `halo_starter_script.ipynb`  

### Region Files
- Very large HDF5 files  
- Contain ~500–1500 halos  
- Used in:
  - `region_simple_starter_script.ipynb`
  - `region_detailed_starter_script.ipynb`

Full region datasets are not included due to size. See the website for download instructions.


## Getting Started

```bash
git clone https://github.com/emilytroutman0/renaissance_starter.git
cd renaissance_starter
pip install h5py numpy matplotlib scipy
jupyter lab
