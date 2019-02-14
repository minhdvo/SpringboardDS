# PROJECT II
Salt Identification in subsurface of reservoir
## Problem 
Seismic data is collected using reflection seismology, or seismic reflection. The method needs a controlled seismic source of energy (such as compressed air or a seismic vibrator and sensors record the reflection from rock interfaces within the subsurface). The recorded data is then processed to generate a 3D view of earth’s interior. Reflection seismology is similar to X-ray, sonar and echolocation. <br>
One of the challenges of seismic imaging is to identify the part of subsurface which is salt. The presence of salt makes it both simple and difficult to identify. The lower density of salt leads to the faster seismic velocity than its surrounding rock surfaces. So, this difference in seismic velocity generates a sharp reflection at the salt-sediment interface and also create some problems with seismic imaging.
## Goals 
The aim of this project is to build a good model to identify if a subsurface target is salt or not.
## Data source
All data are come from kaggle dataset (total data is around 200 MB). They included train and test set in zipped files.
https://www.kaggle.com/c/tgs-salt-identification-challenge/data <br>
The data is a set of images chosen at different locations and random in the subsurface. The images are 101 x 101 pixels and each pixel is classified as either salt or sediment. In addition, the depth of the imaged location is provided for each image. 
## Approach
- Use google colab notebook for running python notebook
- Download data from Kaggle into my drive, unzip data files 
- Copy them into my colab drive.
- Explore and visualize of train and test set.
- Build a model for image classification
- Evaluate the predicted results.  
## Deliverables 
- Jupyter notebooks 
- Final report
- PowerPoint slides
