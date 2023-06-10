# Casal2-krill-model
This repository contains an integrated, statistical model for Antarctic krill in the U.S. AMLR survey strata ((125,019 km2) of CCAMLR Subarea 48.1. The modeling framwork is Casal2 v22.10 (https://github.com/NIWAFisheriesModelling/CASAL2/releases). 'Casal2 Krill.pdf' describes the model.

The data and configuration files are in the 'config' folder. 'krill.e.txt' is the output from an MPD run of the Casal2 model using the input files in the 'config' folder. This model used AMLR acoustic data converted to krill biomass using db-differencing and the stochastic distorted wave-borne approximation. 'krill.nasc.txt' is the output from an MPD run of the Casal2 model with AMLR acoustic NASC attributed to krill using db-differencing, before being converted to biomass (see 'Casal2 Krill.pdf' for the NASC values prior to being converted to biomass).  'R_krill_figs.pdf' was rendered from the rmarkdown file 'R_krill_figs.rmd'.
