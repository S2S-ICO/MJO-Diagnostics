# MJO Diagnostics Tools

## 1. Overviews
[1] climpred: Verification of weather and climate forecasts
> climpred aims to offer a comprehensive set of analysis tools for assessing the quality of dynamical forecasts relative to verification products (e.g., observations, reanalysis products, control simulations). The package includes a suite of deterministic and probabilistic verification metrics that are constantly expanded by the community and are generally organized in our companion package, xskillscore.

example) </br>
[2] and so forth </br>

## 2. Contents
[1] climred </br>
> ## Numerical Weather Prediction
> - Calculate skill for NWP model GEFS for 6-hourly global forecasts
> ## Subseasonal
> - Calculate skill of a MJO Index of SubX model GEOS_V2p1 as function of daily lead time
> - Calculate skill of a MJO Index of S2S models as function of daily lead time
> - Calculate skill of a MJO Index of SubX model GEOS_V2p1 as function of weekly lead time
> - Calculate skill of S2S model ECMWF for daily global reforecasts
> ## Monthly and Seasonal
> - Calculate ENSO Skill of NMME model NCEP-CFSv2 as Function of Initial Month vs. Lead Time
> - Calculate Seasonal ENSO Skill of the NMME model NCEP-CFSv2
> ## Decadal
> - Demo of Perfect Model Predictability Functions
> - Hindcast Predictions of Equatorial Pacific SSTs
> - Diagnosing Potential Predictability
> - Significance Testing

example) </br>
[2] and so forth </br>
(Contents that are contained in program codes will be described here!)

## 3. Installation Instructions

[1] climpred </br>
> You can install the latest release of climpred using pip or conda:
```sh
pip install climpred[complete]
```
```sh
conda install -c conda-forege climpred
```
> See the "[climpred]" for detailed instructions
</br></br>
(Detailed guide to install program codes will be described here!) </br>
example) </br>
[2] and so forth </br>
It might be useful --but not at all required-- to use the provided iri-dev.yml conda environment file. If so, just follow the usual approach:
```sh
conda env create -f iri-dev.yml
```

## 4. Examples
[1] climpred </br>
> The detailed application of the technique can be checked through the link of each technique.
> ## Numerical Weather Prediction
> - [Calculate skill for NWP model GEFS for 6-hourly global forecasts]
> ## Subseasonal
> - [Calculate skill of a MJO Index of SubX model GEOS_V2p1 as function of daily lead time]
> - [Calculate skill of a MJO Index of S2S models as function of daily lead time]
> - [Calculate skill of a MJO Index of SubX model GEOS_V2p1 as function of weekly lead time]
> - [Calculate skill of S2S model ECMWF for daily global reforecasts]
> ## Monthly and Seasonal
> - [Calculate ENSO Skill of NMME model NCEP-CFSv2 as Function of Initial Month vs. Lead Time]
> - [Calculate Seasonal ENSO Skill of the NMME model NCEP-CFSv2]
> ## Decadal
> - [Demo of Perfect Model Predictability Functions]
> - [Hindcast Predictions of Equatorial Pacific SSTs]
> - [Diagnosing Potential Predictability]
> - [Significance Testing]

</br></br>
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
  [Calculate skill for NWP model GEFS for 6-hourly global forecasts]: https://climpred.readthedocs.io/en/stable/examples/NWP/NWP_GEFS_6h_forecasts.html#
  [Calculate skill of a MJO Index of SubX model GEOS_V2p1 as function of daily lead time]: https://climpred.readthedocs.io/en/stable/examples/subseasonal/daily-subx-example.html
  [Calculate skill of a MJO Index of S2S models as function of daily lead time]: https://climpred.readthedocs.io/en/stable/examples/subseasonal/daily-S2S-IRIDL.html
  [Calculate skill of a MJO Index of SubX model GEOS_V2p1 as function of weekly lead time]: https://climpred.readthedocs.io/en/stable/examples/subseasonal/weekly-subx-example.html
  [Calculate skill of S2S model ECMWF for daily global reforecasts]: https://climpred.readthedocs.io/en/stable/examples/subseasonal/daily-S2S-ECMWF.html
  [Calculate ENSO Skill of NMME model NCEP-CFSv2 as Function of Initial Month vs. Lead Time]: https://climpred.readthedocs.io/en/stable/examples/monseas/monthly-enso-subx-example.html
  [Calculate Seasonal ENSO Skill of the NMME model NCEP-CFSv2]: https://climpred.readthedocs.io/en/stable/examples/monseas/seasonal-enso-subx-example.html
  [Demo of Perfect Model Predictability Functions]: https://climpred.readthedocs.io/en/stable/examples/decadal/perfect-model-predictability-demo.html
  [Hindcast Predictions of Equatorial Pacific SSTs]: https://climpred.readthedocs.io/en/stable/examples/decadal/tropical-pacific-ssts.html
  [Diagnosing Potential Predictability]: https://climpred.readthedocs.io/en/stable/examples/decadal/diagnose-potential-predictability.html
  [Significance Testing]: https://climpred.readthedocs.io/en/stable/examples/decadal/Significance.html
