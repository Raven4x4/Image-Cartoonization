# Image-Cartoonization
This repository contains the implementation of a project to convert images into cartoon-like images using various image processing techniques and machine learning models.

# Introduction
The "Image-Cartoonization" project aims to transform regular images into cartoon-style images using advanced image processing and machine learning techniques. This project applies filters and algorithms to achieve a cartoon-like effect on input images.

# Methodology
1. Loading Images
The first step is to load the images from the dataset. This involves reading the image files and converting them into a format suitable for processing.

2. Preprocessing
Preprocessing involves applying various techniques to prepare the images for cartoonization. This includes:
    1. Resizing and Normalizing: Ensuring all images are of the same size for consistent processing.
    2. Edge Detection: Highlighting the boundaries within an image, which is crucial for creating a cartoon effect.
3. Cartoonization
Cartoonization involves applying various filters and techniques to create a cartoon-like effect. This includes:
    1. Bilateral Filtering: Smoothing the image while preserving edges to achieve a cartoonish look.
    2. Color Quantization: Reducing the number of distinct colors in the image to make it look more like a cartoon.
    3. Combining Effects: Merging the edge-detected image with the filtered and quantized image to create the final cartoon effect.

# Results
The results of the image cartoonization process will be displayed within the notebook, showing the original and cartoonized images side by side for comparison.
