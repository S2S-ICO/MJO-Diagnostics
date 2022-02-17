# MJO Diagnostics Tools

## 1. Overviews
[1] climpred: Verification of weather and climate forecasts
> climpred aims to offer a comprehensive set of analysis tools for assessing the quality of dynamical forecasts relative to verification products (e.g., observations, reanalysis products, control simulations). The package includes a suite of deterministic and probabilistic verification metrics that are constantly expanded by the community and are generally organized in our companion package, xskillscore.


## 2. Contents
example) </br>
[1] climred </br>
> - Calculate skill for NWP model GEFS for 6-hourly global forecasts
> - Calculate skill of a MJO Index of SubX model GEOS_V2p1 as function of daily lead time
> - Calculate skill of a MJO Index of S2S models as function of daily lead time
> - Calculate skill of a MJO Index of SubX model GEOS_V2p1 as function of weekly lead time
> - Calculate skill of S2S model ECMWF for daily global reforecasts
> - Calculate ENSO Skill of NMME model NCEP-CFSv2 as Function of Initial Month vs. Lead Time
> - Calculate Seasonal ENSO Skill of the NMME model NCEP-CFSv2
> - Demo of Perfect Model Predictability Functions
> - Hindcast Predictions of Equatorial Pacific SSTs
> - Diagnosing Potential Predictability
> - Significance Testing

(2) and so forth </br>
(Contents that are contained in program codes will be described here!)

## 3. Installation Instructions
(Detailed guide to install program codes will be described here!)

example) </br>
[1] climpred </br>
> You can install the latest release of climpred using pip or conda:
'''sh
pip install climpred[complete]
'''
'''sh
conda install -c conda-forege climpred
'''
> See the "[climpred]" for detailed instructions

[2] and so forth </br>
It might be useful --but not at all required-- to use the provided iri-dev.yml conda environment file. If so, just follow the usual approach:
```sh
conda env create -f iri-dev.yml
```

## 4. Examples
(Detailed guide to run program codes will be described here!)

example)

```sh
MJODiagnostics(Parameter,...)
```

## 5. Issues
### Patch note
Please use the "Issues" tab at the top to request issues that need to be addressed.


## 6. Contributors & Acknowledgements
(Contributors and relevant Acknowledgements for program codes will be listed here!)

example)

The MJOWG wishes to acknowledge and thank U.S. CLIVAR and International CLIVAR for supporting this working group and its activities </br>
by MJO Simulation Diagnostics

## 7. How to cite
(Citation for program codes will be listed here!)

example)

National Center for Atmospheric Research Staff (Eds). Last modified 08 Oct 2013. "[The Climate Data Guide: MJO]: Madden-Julian Oscillation Diagnostics." 

## 8. Disclaimer
Any claims against the Institute stemming from the use of any GitHub-related project will be governed.


  [climpred]: https://climpred.readthedocs.io/en/stable/examples.html#subseasonal
  [Manual]: https://climatedataguide.ucar.edu/climate-data/mjo-madden-julian-oscillation-diagnostics
  [The Climate Data Guide: MJO]: https://climatedataguide.ucar.edu/climate-data/mjo-madden-julian-oscillation-diagnostics
