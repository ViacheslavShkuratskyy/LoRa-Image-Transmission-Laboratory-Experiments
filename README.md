# LoRa-Image-Transmission-Laboratory-Experiments
Test image and image-characterisation data for LoRa image transmission experiments.

Repository Structure
This repository contains the images, experimental data and analysis files associated with the laboratory-based LoRa image transmission experiments conducted under controlled conditions using a Faraday cage.

Images/n
The images/ directory contains the test images used in the study and is organised as follows:
  * Images/butterflies.jpg: The butterfly image used for quantitative image-characteristic analysis and comparison with the 24 images from the Kodak Lossless True Color Image Suite.
  * Images/Originals/: Subdirectory contains the image files and image versions used as inputs for the LoRa transmission experiments.
  * The Kodak images were used exclusively for image-characteristic comparison and were not used in the LoRa transmission experiments.

Image_Analysis
The image_analysis/ directory contains the quantitative image characteristics results obtained for the selected butterfly test image and the 24 reference images from the Kodak Lossless True Color Image Suite. It contains the following files:
 * image_characteristics.csv: Contains the calculated image characteristics, including colourfulness, grayscale contrast, edge density, GLCM texture features and local entropy. These measurements were used to compare the butterfly image with the Kodak reference images.
 * RGB_statistics.csv – Contains the statistical characteristics of the RGB colour channels, including their mean values, variances and Shannon entropy.

