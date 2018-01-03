# Ondřejov Spectra Preprocessing

This work aims to find correct preprocessing techniques for spectral data
from [Ondřejov CCD700 archive][2].
These preprocessing method as cleaning, balancing, scaling should help
to increase classification accuracy of neural network.
Furthermore, it also seek to get more insight into application of machine
learning to spectral data
because there is the [LAMOST][3] spectra archive
which contains vast amount of unexplored data of this kind.

[2]: http://voarchive.asu.cas.cz/ccd700/q/web/form
[3]: http://www.lamost.org/public/?locale=en

This work originates as seminar work for Data Preprocessing course at FIT CTU.

## Data

Spectral data from Ondrejov CCD700 spectrograph are aggregated into CSV file
by code in [ondrejov-dataset][1] repository.
The file `ondrejov-dataset.csv` should be placed into root of this repository.

[1]: https://github.com/podondra/ondrejov-dataset

## Outline

1. [ ] data visualization, find incorrectly classified spectra
2. [ ] data cleaning
3. [ ] feature classification, all are continuous?
4. [ ] create new features, not reasonable
5. [ ] data balancing, do a lot of work here
6. [ ] data scaling, see what's best for neural network
7. [ ] meanwhile measure accuracy, cross validation
8. [ ] try to fit parametric model, 3 Gaussians?
