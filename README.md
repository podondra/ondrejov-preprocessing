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

## Setup

It is recommended to create virtual enviroment to avoid dependency problems:

```bash
$ python3.6 -m venv venv
$ source venv/bin/active
$ pip install -U pip wheel setuptools
$ pip install -r requirements.txt
```

## Data

Spectral data from Ondrejov CCD700 spectrograph are aggregated into CSV file
by code in [ondrejov-dataset][1] repository.
The file `ondrejov-dataset.csv` should be placed into root of this repository.

[1]: https://github.com/podondra/ondrejov-dataset
