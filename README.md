
# Coin Detection using Morphological Operators

-----

This repository contains a Jupyter notebook that demonstrates the process of *coin detection* in an image using *Morphological Operators* and computer vision techniques.

## Project Objective

The main goal of this project is to apply image processing techniques, specifically morphological operations, to accurately detect and count the number of coins present in an image.

## Technologies & Libraries

The following Python libraries are used in this project:

  * **OpenCV (cv2): Used for reading the image and performing image processing and morphological operations.
  * **NumPy (numpy): Used for numerical operations, especially with image arrays.
  * **Matplotlib (matplotlib.pyplot): Used for displaying the images and visualization of results.

## Files

  * Coin-Detection.ipynb: The main Jupyter notebook containing the code and analysis.
  * CoinsA.png: (Assumed) The input image file read by the notebook for coin detection.

## Methodology Overview

The notebook implements a coin detection pipeline that typically involves the following key steps:

1.  *Image Loading*: Reading the input image (CoinsA.png).
2.  *Preprocessing*: Converting the image to grayscale and applying filtering/thresholding.
3.  *Morphological Operations*: Application of techniques like erosion and dilation to clean the image and separate overlapping objects (coins).
4.  *Blob Detection*: Using a SimpleBlobDetector to identify and locate the coins in the processed image.
5.  *Result*: Drawing circles around the detected coins and printing the final count.

## Execution

1.  Ensure you have the required libraries installed:
    bash
    pip install opencv-python numpy matplotlib jupyter
    
2.  Place the CoinsA.png image file in the same directory as the Coin-Detection.ipynb notebook.
3.  Open the notebook in a Jupyter environment:
    bash
    jupyter notebook Coin-Detection.ipynb
    
4.  Run all cells in the notebook sequentially to execute the coin detection process.

## Sample Result

The execution of the notebook successfully identifies and counts the coins in the image.

*Output:*


Number of coins detected: 9


-----

**Note:** This notebook was created as a Class Task for **Unit - 04 - Morphological Operators.
