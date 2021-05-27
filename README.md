# Mini Project - Image Classification

The aim of this mini project was to test object-based land cover classificaion schemes using python, semi automating the process.

Packages used were added to the g420 environment.

An orthophoto of the Wellington waterfront was downloaded from LINZ (30cm pixel resolution) for classification.
<img src="https://github.com/SofyaGrace/Mini-Project/blob/main/Wellington.JPG" width="60%"></img> 



A training data shape file for the image was created using QGIS with 5 classes assigned (water, grass, vegetation, concrete, buildings).

<img src="https://github.com/SofyaGrace/Mini-Project/blob/main/Control_points.JPG" width="60%"></img> 



Three different classification schemes were used to segment the image. These include Slic, Quickshift, and Felzenszwalb. 

# Links to Jupyter Notebooks:

Slic Classification:
https://github.com/SofyaGrace/Mini-Project/blob/main/G420%20Project%20-%20Slic.ipynb

Quickshift Classification:
https://github.com/SofyaGrace/Mini-Project/blob/main/G420%20Project%20-%20Quickshift.ipynb

Felzenszwalb Classification:
https://github.com/SofyaGrace/Mini-Project/blob/main/G420%20Project%20-%20Felzenszwalb.ipynb


# Segmented images displayed in QGIS:

Slic Segmentation: 

<img src="https://github.com/SofyaGrace/Mini-Project/blob/main/SlicSegmentation.JPG" width="40%"></img>

Quickshift Segmentation: 

<img src="https://github.com/SofyaGrace/Mini-Project/blob/main/QuickshiftSegmentation.JPG" width="40%"></img>

Felzenszwalb Segmentation:  

<img src="https://github.com/SofyaGrace/Mini-Project/blob/main/FelzenszwalbSegments.JPG" width="40%"></img>



# Results 

Slic Classification:
<img src="https://github.com/SofyaGrace/Mini-Project/blob/main/Slic.jpg" width="90%"></img> 

Quickshift Classification:                                                                                                 
<img src="https://github.com/SofyaGrace/Mini-Project/blob/main/Quickshift.jpg" width="90%"></img> 
                                                                                                       
Felzenszwalb Classification:                                                                                                       
<img src="https://github.com/SofyaGrace/Mini-Project/blob/main/Felzenszwalb.jpg" width="90%"></img> 
The strong point of this segmentation tool was its classification of the complicated rooftops in the lowerleft corner of the image (the best out of the three tools).
It also managed to pick out small features such as cars and people unlike the other tools.
The outlines of concrete, grass and water areas were well defined, however in each of these areas it has confused parts as being buildings. 

