# HRecPrediction

This project constructs a Convolutional Neural Network (CNN) model to predict the number of hydrogen recombinations in photo-evaporating gas structures during the reionization of the Universe in the first billion years of cosmic history.

This is a collaboration project between Hyunbae Park and Tilman Hartwig at the University of Tokyo from 2020.

We aim to train a CNN model on existing simulation data to learn the relationship between the initial configuration of gas density structures and the number of recombinations they will undergo over the course of a photo-evaporation simulation.

Ideally, an accurate CNN model would eliminate the need for computationally expensive numerical simulations, saving significant computing time and human effort.

- Paper on photo-evaporation simulation by Hyunbae Park: https://ui.adsabs.harvard.edu/abs/2016ApJ...831...86P/abstract

The list of contents are as follows.
[1] Main Jupyter noteboook: HRecPredict.ipynb.
[*] Recombination, local density, and particle density data from simulation: simData.h5. Due to its large file size, we provide a separate link to a shared Dropbox link. 
https://www.dropbox.com/scl/fi/fvjvet9dvz7ha56z9amt8/simData.h5?rlkey=trk8q6unijh99pj1octeuseak
