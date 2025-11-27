## LSST@Latam 2025 - Mexico

# Tutorial : Effcient Angular Masking Generation for Wide-field Astronomical Surveys

This repository contains the notebooks used during the tutorial and the resulting mask pipelines. Clone this repo with `git clone https://github.com/samotracio/LSSTLatam2025.git` to make a copy in your disk. Data files are hosted externally (due to the 100MB file limitation) and can be obtained following the links below.

* **Example HSC-SSP (170MB):** dataset here -> [https://tinyurl.com/dataHSC](https://tinyurl.com/dataHSC) or [here](https://drive.google.com/file/d/1Fft9E9uD1eXs-8Dxb8bp5ou1bEtCTkgr/view?usp=sharing)

* **Example Rubin (320MB):** dataset here -> [https://tinyurl.com/dataNES](https://tinyurl.com/dataNES) or [here](https://drive.google.com/file/d/1ud-aePsMKBpfEsAntczI3CDBoyp-wab8/view?usp=sharing)

## Pre-requisites
It is advisable to create a clean Anaconda (linux) environment as detailed below:

```
conda create -n mexdemo python=3.11
conda activate mexdemo
pip install skykatana
pip install jupyterlab
pip install rubin-scheduler
```
The following are optional:
```
pip install ipympl  (for interactive mataplotlib figures)
pip install -U ipyaladin anywidget ipywidgets (for interactive Aladin plots)
pip install jupyterlab_execute_time  (for cell execution time counter and historial) 
pip install jupyter-resource-usage  (for memory usage indicator)
```

## Skykatana Code Repository
Github repo : [https://github.com/samotracio/skykatana](https://github.com/samotracio/skykatana)

ReadTheDocs : [https://skykatana.readthedocs.io/en/latest/](https://skykatana.readthedocs.io/en/latest/)

-----------------


### Useful links
HATS : [https://github.com/astronomy-commons/hats](https://github.com/astronomy-commons/hats)

LSDB : [https://github.com/astronomy-commons/lsdb](https://github.com/astronomy-commons/lsdb)

LSDB Docs : [https://docs.lsdb.io/en/latest](https://docs.lsdb.io/en/latest/)

LSDB Datasets : [https://data.lsdb.io/](https://data.lsdb.io/)

Healsparse : [https://github.com/LSSTDESC/healsparse](https://github.com/LSSTDESC/healsparse)

MocPy : [https://github.com/cds-astro/mocpy](https://github.com/cds-astro/mocpy)



