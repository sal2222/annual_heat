# annual_heat

## Heat Stress Illness Outcomes and Annual Indices of Outdoor Heat at U.S. Army Installations

This project / repository includes code used for re-analysis of work in https://github.com/sal2222/annual_hsi, following discovery of mismatched climate variables.


## Markdown files

1. `annual_indices`

    - compile annual index tables for temperature/heat exposures (Absolute and Relative)


2. `annual_data`

    - join annual outcome data with annual index data


3. `models` 

    - load and prepare data
    - create outcome-specific datasets
    - negative binomial models (with and w/out year term), non-bootstrap
    - 2-year block bootstraps (2k resamples, `basic` and `bca` CIs)
    - 3-year block bootstraps (2k resamples)
    - standard bootstrap (2k resamples)

4. `model_assess`

    - figures displaying rate ratios for active-duty HSI encounters at 10 CONUS U.S. Army installations per 1° increase in annual index of heat from 2-year block bootstrap negative binomial models with basic (empirical) confidence intervals based on 2,000 replicates, controlling for installation-level effects and long-term time trends. Temperature, HI, and WBGT categories reflect annual mean values in °F
    
    - evaluation statistics for negative binomial models


5. `tables_figures`

  - additional tables and figures



