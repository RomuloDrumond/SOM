# Overview

This repository contains a Jupyter Notebook with a python implementation of Self-Organizing Maps (SOM) on CPU and GPU, you can find a bit of theory and the implementation on it. To better visualize the notebook go to:
https://nbviewer.jupyter.org/github/RomuloDrumond/SOM/blob/master/SOM.ipynb

To install dependencies run `pip install -r requirements.txt` on the main directory.

### Important libraries used:

* Pandas, for loading and preprocessing of the data;
* Sklearn, for scaling features;
* Plotly, for beautiful graphs and a cool training animation;
* Numpy, for matrices computation on CPU version;
* PyTorch, for matrices computations on GPU version;
* Scipy, for the fast 'cdist' function;
* tqdm, for amazing progress bars when training;
