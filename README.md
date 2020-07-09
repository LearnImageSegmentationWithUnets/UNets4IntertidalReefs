# UNets4IntertidalReefs
Teaching resources for image segmentation with U-Nets (a type of deep neural network).

There are five courses that can be accessed and run online through Google Colab

This repository contains versions of those courses that may be adapted for your own purposes, running on the computers you manage and have access to.

----------------------
Step 1: get the code

open an anaconda command window

`git clone --depth 1 https://github.com/MARDAScience/UNets4IntertidalReefs.git`

----------------------
Step 2: create the conda environment

`cd UNets4IntertidalReefs`

`conda env create -f unet_imseg.yml`

`conda activate unet_imseg`

----------------------
Now, you have a few options

1.   Run through the workflows (parts 1 through 5) as python scripts, in sequence

`cd scripts`
`python _part1_of_5.py`
`python _part2_of_5.py`
`python _part3_of_5.py`
`python _part4_of_5.py`
`python _part5_of_5.py`

2.   Run through the workflows as jupyter notebooks

`cd notebooks`
`jupyter notebook`

(open the notebooks from your browser)

3. Train a model on your own data

a. make a new folder inside data and organize your images and label images similarly, into train, test and validation folders
b. make a config file like those for the other data sets
c. copy and adapt the workflow to your needs, modifying (at least) the paths to your data, and other specifics
