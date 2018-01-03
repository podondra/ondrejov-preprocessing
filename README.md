# Ondrejov Spectra Preprocessing

TODO write intro.

## Data

Spectral data from Ondrejov CCD700 spectrograph are aggregated into CSV file
by code in [ondrejov-dataset][1] repository.
The file `ondrejov-dataset.csv` should be placed into root of this repository.

[1]: https://github.com/podondra/ondrejov-dataset

## Outline

1. [ ] data visualization, find incorrectly classified spectra
2. [ ] data cleaning
3. [ ] feature classification, all are continuos?
4. [ ] create new features, not reasonable
5. [ ] data balancing, do a lot of work here
6. [ ] data scaling, see what's best for neural network
7. [ ] meanwhile measure accuracy, cross validation
