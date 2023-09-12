The `irg` package is based on the procedure proposed in Heerah et al.
(2021).

``` r
library(irg)
```

The functions made available allow to perform Granger-Causal testing for
signals that are sampled at the same but irregularly spaced time points.
Before using the functions in the package, the signals need to be
pre-processed such that they are detrended (mean-stationary) and
standardized (normalized). Below we show some examples of possible ways
of pre-processing the signals as well as how to use the main functions
of the package.

# References

Heerah, Sachin, Roberto Molinari, Stéphane Guerrier, and Amy
Marshall-Colon. 2021. “Granger-Causal Testing for Irregularly Sampled
Time Series with Application to Nitrogen Signalling in Arabidopsis.”
*Bioinformatics* 37 (16): 2450–60.
