# CO2-Toy-Model
This implements a simple single-layer idealized greenhouse atmosphere that uses HITRAN data to calculate atmospheric opacities, then computes the atmospheric and surface temperature of a toy Earth at different CO2 concentrations.


### Setup Instructions

Most importantly, unzip the `greenhouse-absorptions.json` file! Then you should be able to run almost everything in the notebook using the precomputed molecular cross sections. 

Optionally, you can install HAPI (the HITRAN API) in your Jupyter environment by uncommenting the line at the very top. This will allow you to enable the `use_HITRAN` option and dynamically update the molecular cross sections (e.g. to add other gases or different temperature/pressure conditions)
