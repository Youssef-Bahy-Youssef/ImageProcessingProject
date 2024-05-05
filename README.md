# Image Compression using 2D DCT

## Overview

This project implements a simple image compression algorithm using 2D Discrete Cosine Transform (DCT). The algorithm reads an input image, processes each of its color components (red, green, and blue) in blocks of 8 × 8 pixels, and converts each block into the frequency domain using 2D DCT. The algorithm then retains only a few coefficients while discarding the rest, thus achieving compression. Finally, it decompresses the image by applying the inverse 2D DCT to the retained coefficients and measures the quality of the decompressed image using Peak Signal-to-Noise Ratio (PSNR).

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
   git clone https://github.com/EngYoussefBahy/ImageProcessingProject.git

2. Run ImageProcessing.ipynb
  ```bash
  jupyter notebook 

