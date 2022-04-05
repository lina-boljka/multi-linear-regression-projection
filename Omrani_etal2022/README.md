## Omrani et al 2022

This folder includes the data and code used for producing multilinear regression based statistical projections in Omrani et al 2022 [doi:NPJCLIMATSCI-00698]. 

File "AMO_etc_projection.ipynb" is a notebook with the code and additional detailed text & instructions on how to use it.
Folders "txts" and "nc" include detrended timeseries and their trends, respectively. 

The code can be run for different parameters used in Omrani et al 2022 as well as some additional ones (like northern and southern European precipitation). The code typically uses multi-linear projection to predict specific variable's future timeseries from 4 variables: North Atlantic Oscillation (NAO), Atlantic Multidecadal Oscillation (AMO), sea ice, and the variable itself. For details see the manuscript or notebook itself.

File "AMO_etc_projection.ipynb" shows one example of using this code (for projecting AMO into the future).

### Interactive Notebook

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lina-boljka/multi-linear-regression-projection.git/HEAD)

Navigate <a href="https://mybinder.org/v2/gh/lina-boljka/multi-linear-regression-projection.git/HEAD">HERE</a> to folder "Omrani_etal2022" to find interactive version of the provided Notebook, where parameters can be changed to see results/projections for different variables.
* We recommend changing only predictand parameters under "RUN FUNCTIONS" section (1). Everything else should then automatically work with the provided parameters - only the boxes/scripts below must be rerun upon chaning parameters. Results will appear under "PLOT" section.
* Number of predictors can also be changed in section (2) of "RUN FUNCTIONS", but that would be more sophisticated and was not used in the manuscript.
* If links above are not working copy & paste this into browser: https://mybinder.org/v2/gh/lina-boljka/multi-linear-regression-projection.git/HEAD

### Citation
* Omrani, N.-E., N. S. Keenlyside, K. Matthes, L. Boljka, D. Zanchettin, J. H. Jungclaus, and S. W. Lubis, 2022: Atlantic atmosphere-ocean multidecadal oscillation: a key for improved near-future climate projection. npj Climate and Atmospheric Science, accepted. [doi:NPJCLIMATSCI-00698]
