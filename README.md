[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/openalea-training/niab_workshop/HEAD?labpath=%2Ftree%2Fmain%2Flpytraining)

# NIAB workshop Agenda

Frederic Boudon & Christophe Pradal
## Monday 15th November

 - Welcome
 - Workshop introduction
 - Short presentation of the participants

 - Introduction to 3D shoot and root plant modelling
 - Short Introduction to OpenAlea

Lunch

 - Topological and Geometrical representation of Plant Architecture
 - 3D Phenotyping of Plant Architecture
    - Course + Tutorials

## Tuesday 16th November

 - Simulation of Plant Architecture using L-Systems 
    - Full-day Hands-on courses and tutorials with L-Py

## Wednesday 17th November

 - Personal modelling projects 

# Installation

## Conda install

### Conda Installation

[Conda](https://docs.conda.io) is a package manager that can be installed on Linux, Windows, and Mac.
If you have not yet installed conda on your computer, follow these instructions:

[Conda Installation](https://conda.io/projects/conda/en/latest/user-guide/install/index.html). Follow instructions for Miniconda.

[Conda Download](https://docs.conda.io/en/latest/miniconda.html). Use the Python 3.8 based installation.

#### Install Mamba

For fastest installation, install Mamba:

    conda install mamba -c conda-forge

### Get environment.yml

The file is available in the github repository. Clone it or retrieve it.
Then, create a new conda environment:

    mamba env create -f environment.yml

### Activate the env

    conda activate lpytraining

