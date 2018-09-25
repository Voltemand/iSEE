# iSEE 1.1.9

* Added a `NEWS.md` file to track changes to the package.
* Fix compatibility with `DelayedArray` assays.

# iSEE 1.1.8

* Extend unit test coverage.
* Move generics to separate file.
* Minor fix to `annotateEnsembl`.
* Update list of functionalities in README.

# iSEE 1.1.7

* Resolved BiocManager message.

# iSEE 1.1.6

* Minor fix for Windows unit test.

# iSEE 1.1.5

* New panel colors.
* Control arguments to custom panels through action buttons.
* Distinguish visible from active arguments for custom panels.

# iSEE 1.1.4

* Split `?defaults` help page by panel type.
* Generalized support for custome data plots and statistics tables.

# iSEE 1.1.3

* Add new _Sample assay plot_ panel type.
* Extend documentation.
* Split vignette into three: basic, advanced, ExperimentColorMap.
* Fix initialization of reduced dimensions with a single plot axis choice.
* Substitute discouraged use of `sapply`.
* Moved roxygen `importFrom` instructions closer to the relevant code.
* Increase unit test coverage.
* Consistent use of "colormap" through the package.
* Update installation instructions.
* Add CITATION file.
* Add Figure 1 of article in README.

# iSEE 1.1.2

* Enable faceting by row and column, with appropriate updates to brush and lasso.
* Enable shaping on data points.
* Minor fix of jitter for violin and square plots.
* INTERNAL: Enable storage of additional `plot.data` beyond `X` and `Y` in `all.coordinates`. See constant `.allCoordinatesNames`. Necessary for correct behaviour of brushes on faceted plots.

# iSEE 1.0.1

* Rename feature expression plots to feature assay plots, for generality.

# iSEE 0.99.3

* Custom tours can be restarted via the dropdown menu button, overwriting the default tour.
* Add functionality to provide a custom title to be displayed in the app.
* Preserve data points and width ratio upon zoom on discrete variables.

# iSEE 0.99.2

* Add functionality for providing additional custom tours, to be launched directly upon starting the app.

# iSEE 0.99.1

* Add grid-based visual point downsampling for faster plotting, including control of resolution.
* Add button _Clear features_ for heat maps.
* Reorganize buttons in heat map panels.
* Maintainer badge transferred to Federico.

# iSEE 0.99.0

* Initial submission to _Bioconductor_.
