# ✨ 22AIE313 - COMPUTER VISION & IMAGE PROCESSING ✨ ASSIGNMENT 1
  
Roll : CH.EN.U4AIE22015 | CH.EN.U4AIE22050  
Name : Guruprasath M R  | Shree prasad M

## Overview

This assignment involves various image processing techniques using Python libraries such as OpenCV, NumPy, and scikit-image. The tasks include:

1. **Loading and Filtering Noisy Images**: Applying different filters to noisy images and evaluating their performance using PSNR and SSIM metrics.
2. **Binary Segmentation**: Implementing binary segmentation algorithms like K-Means and Otsu's Thresholding.
3. **Multi-Region Segmentation**: Applying multi-region segmentation algorithms such as Felzenszwalb's algorithm, SLIC, and Mean Shift.
4. **Combining Segmentations**: Combining binary and multi-region segmentations and refining the results.
5. **Evaluation**: Evaluating the segmentation results using metrics like Variation of Information (VI), Adapted Rand Error (ARE), and Dice Coefficient.

## Problem Statement

The objective of this assignment is to explore and implement various image processing techniques to enhance and segment noisy images. The key challenges include:

- Effectively reducing noise in images while preserving important details.
- Accurately segmenting images into meaningful regions using both binary and multi-region segmentation techniques.
- Combining different segmentation methods to improve overall segmentation quality.
- Evaluating the performance of the implemented techniques using appropriate metrics.

## Dependencies

- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- scikit-image
- scikit-learn
- pandas
- tqdm

## Instructions

1. **Setup**: Ensure all dependencies are installed. You can use the following command to install the required packages:
    ```bash
    pip install opencv-python-headless numpy matplotlib scikit-image scikit-learn pandas tqdm
    ```

2. **Run the Notebook**: Open the `assignment.ipynb` file in Jupyter Notebook or Jupyter Lab and run the cells sequentially.

3. **Data**: Place your noisy images in the `noisy_images` folder.

## Code Structure

- **Loading and Filtering Noisy Images**:
    ```python
    ...existing code...
    ```

- **Binary Segmentation**:
    ```python
    ...existing code...
    ```

- **Multi-Region Segmentation**:
    ```python
    ...existing code...
    ```

- **Combining Segmentations**:
    ```python
    ...existing code...
    ```

- **Evaluation**:
    ```python
    ...existing code...
    ```

## Results

The results of the segmentation and evaluation are printed in tabular format and visualized using Matplotlib. The best filters and segmentation methods are determined based on the evaluation metrics.

## Conclusion

This assignment demonstrates the application of various image processing techniques and their evaluation. By combining binary and multi-region segmentation methods, we can achieve more detailed segmentation results, especially in challenging conditions such as low-light night photos. The combination and refinement of different segmentation methods significantly improve the overall segmentation quality.
