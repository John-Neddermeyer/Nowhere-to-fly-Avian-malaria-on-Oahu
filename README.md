# Nowhere-to-fly-Avian-malaria-on-Oahu
This repository contains the analysis pipeline for the manuscript: 
"Nowhere to fly: Avian malaria is ubiquitous from ocean to summit on a Hawaiian island" DOI:10.1016/j.biocon.2023.109943.

The repository does not contain all exploratory analayses, but should provide enough detail to understand analyses approach and methods. Please reach out with any questions.

# Modeling Approach
The goal of the analysis was to evaluate the relationship between avian malaria host prevalence and host identity, environmental metrics, host community 
composition, and human land use metrics on the island of Oʻahu. Briefly, we fit binomial GLMs, and used a combination of AIC and non-parametric 
bootstrapping to identify the top predictor set for determining if an avian host was infected with malaria.

This repository also contains an additional Area Under the Reciver Operator Curve analysis that was not presented in the manuscript, where 10 rounds of 
10-fold cross-validation were used to determine the predictive accuaracy of our top models
