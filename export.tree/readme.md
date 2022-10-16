[![DOI](https://zenodo.org/badge/552149683.svg)](https://zenodo.org/badge/latestdoi/552149683)

# Samoan Passage CTD/LADCP Data Archive

Stationary CTD/LADCP data from the 2012 (RR1209) and 2014 (TN305) Samoan Passage cruises.

The data were collected under National Science Foundation grants OCE-1029268 and OCE-1029483.

Data are stored in human-readable format at https://osf.io/up5j4/ and can be downloaded manually from there.

A repository containing data in *git-annex* / *datalad* format is located at https://osf.io/un9pb/ and connected to this repository. To access the data this way, clone the bare dataset repository (without the data files) via:
```
datalad clone https://github.com/gunnarvoet/sp-data-archive-ctd
```
In a second step, obtain the data from the OSF repository via:
```sh
datalad get -r -d sp-data-archive-ctd
```
More information on *git-annex* and *datalad* can be found in the [DataLad Handbook](https://handbook.datalad.org/en/latest/index.html).

The parent Samoan Passage Data Archive repository containing further datasets is located at https://github.com/gunnarvoet/sp-data-archive/.
