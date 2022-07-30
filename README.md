# Underwater-Dataset
Dataset of Underwater images.  All images were taken either with a camera attached to a diver or with an AUV model SPARUS II, property of the University of the Balearic Islands (UIB) and equipped with a stereo rig. Images are representative of multiple different scenarios of the marine environment located in different sites of Balearic Islands, with different textures and lighting conditions. 

This repository contains:

a) A zip file with all the queries 
b) Two zips with all database images. Unzip all database images of both zip files into the same directory.
b) A zip file with 3 matlab file which contain the names of the images included in each dataset. qImageFns.mat corresponds to the queries and dbImageFns.mat to the database, and also the matlab data structures for the NetVLAD training and validation, containing all the needed information regarding the loop closing correspondences via GPS coincidence: ValldemossaGopro3_75_566_1.mat, ValldemossaGopro3_75_566_2.mat  and ValldemossaGopro3_75_566_3.mat
This is to use the dataset for training NetVLAD
