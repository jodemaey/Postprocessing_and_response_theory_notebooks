
# Adaptation of postprocessing EVMOS schemes to model change with response theroy in the QGS model

## General Information

These Jupyter notebooks come as a supplementary material to the article [Correcting for Model Changes in Statistical Post-Processing – An approach based on Response Theory](https://www.nonlin-processes-geophys-discuss.net/npg-2019-57/):

* Demaeyer, J. and Vannitsem, S.: Correcting for Model Changes in Statistical Post-Processing – An approach based on Response Theory, Nonlin. Processes Geophys. Discuss., https://doi.org/10.5194/npg-2019-57, in review, 2019. 

and detail the computations performed to obtain the results therein.

These notebooks aim to show how response theory can help to correct the effect of a model change to an EVMOS post-processing correction.

They also produce the figures of the article and rely on the 2-layer quasi-geostrophic [qgs model](https://github.com/Climdyn/qgs) coupled to an orography.

## About

(c) 2020 Jonathan Demaeyer

See [LICENSE.txt](./LICENSE.txt) for license information.

## Requirements

The present notebooks were tested on a computer with 

* 96 recent cpu cores,
* 64 Gb of RAM,

the whole computation during about an hour for each.
About 9 Gb of hard drive disk space are also used to store temporarily the model's trajectories data.
Less powerfull machines might work provided that one adapts the number of trajectories used
to compute the statistics.

## Installation

To install these notebook, you must first install the [qgs model](https://github.com/Climdyn/qgs) and test that it works properly on your machine. Follow the instructions in the model documentation. Then you must move the present notebooks in the `notebooks` directory and run them with `jupyter-notebook`. In the qgs model main folder, do:

    conda activate qgs
    cd notebooks
    jupyter-notebook

It will open a page in a web browser where you can open and then run the notebooks.

