# survey_simulator
This module generates a list of candidate detections for an input
population of moving objects in a specified list of field pointings.  

The code is based on Naidu et al. objects_in_field
  
## Requirements:  

* python 3  
* spiceypy python library  
* [pyoorb](https://github.com/oorb/oorb) python library   
* other standard python libraries like numpy, pandas, etc.  
* [NAIF SPICE Utilities](https://naif.jpl.nasa.gov/naif/utilities.html)
  
## Setup:  

* Make sure you can import spiceypy, pyoorb, and other libraries in python.  

* Make sure you can run the NAIF SPICE Utility executables from your command line.

* Download the package and run the `DownloadKernels.sh` script
in the `kernels/` folder.  

* Copy the binary `de430.dat` file required by pyoorb into the `data/` folder.

## Usage:
From the `main/` folder run `python main.py input.config`. 
Refer to the documentation under the `doc/` folder for more 
details.

## Note:  
Regularly update and run `DownloadKernels.sh` file to download 
the latest SPICE kernels.
