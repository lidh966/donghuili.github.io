---
title: "Developing a generic data-driven reservoir operation model"
collection: publications
permalink: /publication/2022-07-AWR-GDROM
excerpt: 'This paper is developing a data-driven reservoir operation model that couples hidden Markov model with decision tree model to empirically model daily release policies.'
date: 2022-07-16
venue: 'Advances in Water Resources'
paperurl: 'https://doi.org/10.1016/j.advwatres.2022.104274'
---

### Highlights
* GDROM is formed with a small set of modules and their application conditions.
* GDROM has a consistent and transparent structure simulating daily operation dynamics.
* GDROM is tested with 467 reservoirs with various operation purposes in CONUS.
* GDROM outperforms a tradition decision tree model in daily storage simulation.

### Abstract

This study presents a generic data-driven reservoir operation model (GDROM). The hidden Markov-decision tree (HM-DT) is applied to deriving representative operation modules for a reservoir; a classification and regression tree (CART) algorithm is used to identify the application and transition conditions for the operation modules. These two procedures result in the GDROM that is featured by 1) using a few input variables (inflow, storage, DOY, and PDSI); 2) inheriting merits of decision trees but dramatically reducing model complexity; 3) adopting a consistent and transparent structure (i.e., better interpretability than other machine learning models); and 4) showing a better performance than traditional decision tree models, especially in storage simulation. GDROM is developed for 467 reservoirs with diverse operation purposes in different regions of the Contiguous United States (CONUS), and the testing procedure shows comparable accuracy in release simulation to other ML models; among these reservoirs, 15 are selected for detailed analysis with diverse operational purposes and regulation capacities, from different USGS Water Regions. GDROM presents a ready-to-use reservoir operation model that can be incorporated into a watershed hydrological simulation model.