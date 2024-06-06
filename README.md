# CRREL-KGCNN_data
This repository contains datasets collected by a GoPro 11 using the experimental setup detailed in Chapter 5 of the thesis, and some data taken using the OTT Hydromet Parsivel 2 laser disdrometer.

2_17_segmented contains the manually sampled snowflake images from February 17th, 2024 with measurements of velocity and size. This data may be taken and used in conjunction with the KGCNN detailed in the main KGCNN repository to estimate drag coefficient, mass, density, etc..

GoPro extracted images contains sets of GoPro video extracted into individual frames and downsampled to save storage and computation time. Each file is from January 7th, 2024 with a timestamp and video duration in the name (e.g. 1140 = 11:40, 159min = 1 minute 59 second duration). These files are intended for use with the sample PTV code using Trackpy provided in " GoPro snowflake PTV.ipynb". Currently this code only extracts velocity from the images. There is a discrepancy between the distributions for velocity between snowflakes captured by the GoPro and those captured by the Parsivel 2, and as such the laser disdrometer data was not used in the thesis.
