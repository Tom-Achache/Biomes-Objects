# Biomes & Objects Recognition using Satellite images

## Overview

This is my final project for the class *Deep Learning for Computer Vision* at Columbia University, taught by [Peter Belhumeur](https://www.peterbelhumeur.com).

The idea of this project is to apply Deep Learning to satellite images, in order to recognize biomes and land objects.
I used [Keras](https://keras.io) to build the DL models.

## Setup

This project was made on Google Colab, to speed up the training of the NNs, but can be run without it. In that case, please ignore the first section of the notebook.

## Data description

I used the UC Merced Land Use Dataset, that can be downloaded [here](http://weegee.vision.ucmerced.edu/datasets/landuse.html). I included it in the repository for conveniance. This dataset has 21 classes, which are combinations of biomes (forest, agricultural...) and land objects/constructions (airplane, tennis court...).

Then I expanded this dataset with four additional classes, for which I fetched images on Google Earth and online.

These two dataset can be found in the `Dataset` folder.

## Running the notebook

The notebook to be run is `B-O_Recognition.ipynb`. You can simply run it cell by cell, from the start to the end. The only thing that needs to be changed is the paths used when importing/exporting data.

## Results

On the augmented dataset (UC Merced Land Use + four additional classes), the final accuracy is **95.2%**.
