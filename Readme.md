# Image Processing Techniques with OpenCV and Matplotlib

This Python script demonstrates various image processing techniques using OpenCV and Matplotlib libraries. It applies operations such as histogram equalization, image sharpening, noise reduction, edge detection, filtering, and image compression.

## Overview

The script processes an input image (`rgb.jpg` and `rgb.png`) using OpenCV for various image enhancement and analysis tasks. It utilizes functions from OpenCV and Matplotlib to perform these operations and visualize the results.

## Operations and Techniques Demonstrated

1. **Displaying and Converting Images**:
   - Reads and displays images using OpenCV (`cv2.imread()`) and Matplotlib (`plt.imshow()`).
   - Converts images to grayscale and displays them.

2. **Histogram Equalization**:
   - Enhances the contrast of the grayscale image using histogram equalization (`cv2.equalizeHist()`).

3. **Image Sharpening**:
   - Applies a sharpening kernel (`cv2.filter2D()`) to enhance edges and details.

4. **Noise Reduction**:
   - Uses Gaussian blur (`cv2.GaussianBlur()`) and median filter (`cv2.medianBlur()`) to reduce noise in the image.

5. **Edge Detection**:
   - Computes gradients using Sobel operators (`cv2.Sobel()`) and Laplacian operator (`cv2.Laplacian()`) to detect edges.

6. **Adding Salt and Pepper Noise**:
   - Introduces salt and pepper noise to images with varying densities using a custom function.

7. **Image Compression**:
   - Compresses images using both Pillow (`PIL.Image`) and OpenCV (`cv2.imwrite()` with JPEG compression).

8. **Additional Filters**:
   - Applies Gaussian blur (`cv2.GaussianBlur()`) with different kernel sizes for image smoothing.
   - Implements bilateral filtering (`cv2.bilateralFilter()`) for edge-preserving smoothing.

## Libraries Used

- **OpenCV (`cv2`)**: For image processing operations such as reading, filtering, and transforming.
- **Matplotlib (`plt`)**: For visualizing images and plots.
- **NumPy (`np`)**: For numerical operations on arrays.
- **Pillow (`PIL`)**: For image compression and format conversion.

## Setup Instructions

1. **Install Required Libraries**:
   - Ensure you have installed OpenCV, Matplotlib, NumPy, and Pillow using `pip install`.

2. **Download the Required Images**:
   - Place the images `rgb.jpg` and `rgb.png` in the specified path or adjust the image paths in the script accordingly.

3. **Run the Script**:
   - Execute the Python script (`script.py`) in an environment that supports these libraries (e.g., Jupyter Notebook, Google Colab).

## Usage

- Use this script as a reference for implementing basic to advanced image processing techniques using OpenCV and Matplotlib.
- Customize parameters and functions based on specific requirements for image enhancement, noise reduction, edge detection, and filtering.

This README.md provides an overview of the image processing capabilities demonstrated in the Python script.
