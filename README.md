# UAV-Water-Mosaicking-Code

### Article: Water quality monitoring with UAV mounted multispectral camera in coastal waters
### Authors: Alejandro Román, Antonio Tovar-Sánchez, Adam Gauci, Alan Deidun, Isabel Caballero, Emanuele Colica, Sebastiano D’Amico and Gabriel Navarro

This repository contains a Python workflow that can be used to stitch individual UAV (drone) captures to generate an orthomosaic over aquatic areas. This code arises as a complement to the methodology developed by Windle & Silsbe (2021), and can be applied to any method that retrieves Rrs from RAW data of any multispectral sensor mounted on UAVs. In addition, the code has been prepared for its use with datasets obtained with any UAV sensor.

This repository has two Python codes in the .ipynb format:

- "Georeferencing", which was the method used for the georeferencing of each of the individual captures taken with the Micasense multispectral sensor RedEdge-MX
equipped on the UAV based on the sensor's metadata. This code is a modification of https://github.com/micasense/imageprocessing

- "Merging", which is the novel part of the code used to combine and calculate the average value of each of the UAV captures overlapped with each other.
