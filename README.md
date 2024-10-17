# Color-Chart-Extractor (beta)
Color Chart Extractor is a tool for processing one or more images of color charts, and converting the color samples in those images into data that can be used for various color science or computer vision applications.
## How it works
The tool works by doing the following:
 - Reading the pixel values for each chip of the specified chart type in the uploaded images
 - Averaging the pixel values within each chip to produce a single value, while mitigating noise, etc
 - Displaying or outputting a CSV spreadsheet with R, G, and B values for each color chip in the uploaded image
 ## How do I use it?
 Color Chart Extractor is a Jupyter Notebook hosted in Google Colab. This allows you to easily run the tool without needing to install anything or understand the code that makes the tool work. 

 The Notebook is made up of different "cells" that you can run by clicking the play icon to the left of each cell. This allows you to run and re-run each cell independently. You need to run each cell in order to avoid errors.

 For cells with options, such as the "Download and Display" cell, select the options that you want to use, then run the cell.

 ## I found a bug/I have a feature request
 Get in touch! Shoot me an email at: contact (at) chromanista (dot) com and I'll try to help you out!