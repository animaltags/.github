# Tools for working with data from high-resolution biologging tags

## Overview
High-resolution movement-sensor tags typically include accelerometers to measure body posture and sudden movements or changes in speed, magnetometers to measure direction of travel, and pressure sensors to measure dive depth in aquatic or marine animals. 

A subset of tags include sensors for speed, turning rate (gyroscopes), and sound. This package provides software tools to facilitate calibration, processing, and analysis of such data. 

Tools are provided for: 
* Data Import/export
* Calibration (from raw data to calibrated data in scientific units)
* Visualization (e.g., time-series plots, multiple events overlaid, long-term spectral averages)
* Data Processing (e.g., event detection, derived metrics like jerk and dynamic acceleration, Dive detection and dive parameter calculation, Integrating movement data with other sensors eg acoustic or camera, integrating position data from onboard GPS, visual observations, etc. with movement data
* Statistical Analysis (e.g., track reconstruction, Mahalanobis distance analysis).

## Software
Versions of the animaltags tool kits are available for Matlab/Octave and R, in repositories <https://github.com/animaltags/tagtools_matlab> and <https://github.com/animaltags/tagtools_r>.

A Python version of the tools is under development but is not yet near completion. (<https://github.com/animaltags/tagtools_python>)

## Example Datasets
Example datasets are available in the data repository <https://github.com/animaltags/tagtools_data>.

## More Information
For tutorials, further documentation, and more information see our project webpage: <https://animaltags.org/>

## Funding Sources
This work has been supported by the United States Office of Naval Research, including under Award Number N00014-16-1-3089.
