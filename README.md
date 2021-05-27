# Mini-Project
Image Classification

The aim of this mini project was to test object-based land cover classificaion schemes using python, semi automating the process.

Packages used were added to the g420 environment.

An orthophoto of the Wellington harbour was downloaded from LINZ (30cm pixel resolution) for classification.
<img src="https://github.com/SofyaGrace/Mini-Project/blob/main/Wellington.JPG" width="90%"></img> 



A training data shape file for the image was created using QGIS with 5 classes assigned (water, grass, vegetation, concrete, buildings).


Three different classification schemes were used to segment the image. These include Slic, Quickshift, and Felzenszwalb.



assigned segments to one of 5 classes from supplied training data (water, grass, vegetation, concrete, buildings)
used three different classification schemes to segment the image









Slic classification scheme:
<img src="https://github.com/SofyaGrace/Mini-Project/blob/main/Slic.jpg" width="90%"></img> 

Quickshift classification scheme:                                                                                                 
<img src="https://github.com/SofyaGrace/Mini-Project/blob/main/Quickshift.jpg" width="90%"></img> 
                                                                                                       
Felzenszwalb classification scheme:                                                                                                       
<img src="https://github.com/SofyaGrace/Mini-Project/blob/main/Felzenszwalb.jpg" width="90%"></img> 
