# toxReviewer
R package to analyze toxicological data in summary form.
Data are assumed to be in the form of means and standard deviations (etc.) or numbers responding / numbers on test.

Data entry is convenient although command-based, not GUI-based.

Example (Fisher's exact test) > fe("1/10;5/10")

Statistical functions are largely shells for base R statistics or otherwise published methods. 

Contrast based methods and multiplicity adjustments are emphasized, based on multcomp package (Hothorn et al.)

An S3 approach is implemented for continuous-response data.

