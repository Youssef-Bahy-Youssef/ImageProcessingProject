# Image Compression using 2D DCT

## Overview

The primary goal of this project is to develop an image compression system using **DCT** on 8x8 blocks to efficiently reduce image sizes while maintaining visual quality

## Steps

- Read an input image file.
- Extract and display each of its three color components.
- Compress the image by processing each color component in blocks of 8 × 8 pixels.
- Convert each block into the frequency domain using 2D DCT and retain only a few coefficients.
- Compare the sizes of the original and compressed images.
- Decompress the image by applying inverse 2D DCT to the retained coefficients.
- Measure the quality of the decompressed image using PSNR.


## Used Libraries:
- opencv
- numpy
- pandas
- matplotlib 
- PIL
- scipy

## Usage

1. Clone the repository:


   ```bash
   git clone https://github.com/your-username/image-compression-using-dct.git

2. Run ImageProcessing.ipynb:
   ```bash
   jupyter notebook 
3. Project Description:
[link](https://drive.google.com/drive/folders/1L8eS0gcDDs7jQJ8kjgJQtqpeWrygsE3j)
