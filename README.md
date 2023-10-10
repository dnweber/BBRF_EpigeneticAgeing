# BBRF_EpigeneticAgeing

Data and scripts/code associated with "Epigenetic age estimation in a long-lived, deepwater scorpionfish: insights into epigenetic clock development" D. Nick Weber, Andrew T. Fields, Derek W. Chamberlin, William F. Patterson III, and David S. Portnoy. Submitted to CJFAS.

## Associated data can be found in the "Data" folder, incuding:
- "BBRF_percent_wide_FC.csv" contains the matrix of percent methylation values (post all filtering steps) for the fin clip samples, necessary to recreate the elastic net regression results.
- "BBRF_percent_wide_MU.csv" contains the matrix of percent methylation values (post all filtering steps) for the muscle tissue samples, necessary to recreate the elastic net regression results.
- "BBRF_percent_wide_BothTissues.csv" contains the matrix of percent methylation values (post all filtering steps) for the fin clip and muscle tissue samples, necessary to recreate the elastic net regression results.
- The final training and testing datasets (R objects) for all elastic net regression models presented in the manuscript.

## Associated code can be found in the "Scripts" folder, including:

- "ref_config.file" contains the code and parameters used to create a *de novo* reference genome for blackbelly rosefish.
- "BAYES_GLM_wTissueSex.r" contains code associated with the Bayesian GLM run with 4,000 warm-up/sampling iterations.
- "BAYES_GLM_wTissueSex_50k.r" contains code associated with the Bayesian GLM run with 50,000 warm-up/sampling iterations.
- "95% CI's.Rmd" contains the code necessary to calculate 95% confidence intervals.
- "Elastic Net Regression.Rmd" contains the code necessary to run the elastic net regressions.
