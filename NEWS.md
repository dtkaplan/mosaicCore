
# mosaicCore 0.4.2

* Add `fit_distr_fun()` which fits distribtuions using `MASS::fitdistr()` but returns a function (density, cdf, quantile, or random sampling) instead of just the parameters of the fit.

# mosaicCore 0.4.0

* Additional functions from `mosaic` have been moved here.

* Improvements to `df_stats()` to handle a wider range of stat functions.

# mosaicCore 0.2.0

* Some functions from `mosaic` and `ggformula` have been moved here to support a better dependency structure among the Project MOSAIC packages.  This package is unlikely to be needed in isolation, but functions from this package will be imported into the other packages as needed.  Some will also be re-exported.



