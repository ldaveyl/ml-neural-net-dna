# ml-neural-net-dna

## Introduction

In this repository, DNA sequences are used to build, train and evaluate a neural network in a jupyter notebook.
The main use of this notebook is to demonstrate a typical workflow in PyTorch. More specifically:

 - Loading a dataset
 - Creating a neural network
 - Training a neural network
 - Evaluating the neural network on unseen data
 - Visualizing the performance

## Branch structure

 - master: main branch

## Directory structure

 - **dna_sequence_dataset.csv** Dataset containing 142,698 dna sequences and targets
 - **ml-neural-net-dna.ipynb** Jupyter notebook

## Installation

 1. Create a new conda environment and activate it.  

        conda create --name myenv
        source activate myenv

 2. Install packages

        conda install -c anaconda jupyter
        conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch
        conda install -c anaconda pandas
        conda install -c conda-forge matplotlib
        conda install -c anaconda scikit-learn

## Usage

    jupyter notebook

## Contact

lucas.davey@biscglobal.com
