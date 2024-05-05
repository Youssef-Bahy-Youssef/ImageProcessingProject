# Image Compression using 2D DCT

## Overview

The primary goal of this project is to develop an image compression system using the ** Discrete Cosine Transform (DCT) ** technique applied to 8x8 pixel blocks in a two-dimensional space. Upon compression, the system aims to efficiently reconstruct the image using the Inverse DCT method for each block. By employing this approach, the project endeavors to reduce the size of digital images while preserving their visual integrity, facilitating tasks such as storage optimization and transmission efficiency.
## Features

- Read an input image file.
- Extract and display each of its three color components.
- Compress the image by processing each color component in blocks of 8 × 8 pixels.
- Convert each block into the frequency domain using 2D DCT and retain only a few coefficients.
- Compare the sizes of the original and compressed images.
- Decompress the image by applying inverse 2D DCT to the retained coefficients.
- Measure the quality of the decompressed image using PSNR.
- Plot PSNR against the number of retained coefficients (m) to visualize the trade-off between compression ratio and image quality.

## Used Libraries
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

