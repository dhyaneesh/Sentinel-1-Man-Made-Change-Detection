# Change Detection and Edge Detection

## Overview
This repository contains Jupyter notebooks for processing images using edge detection and change detection techniques. These notebooks utilize various image-processing algorithms to analyze visual data, detect significant changes, and extract edges from images.

## Notebooks

### 1. `Main.ipynb`
This notebook serves as the primary script for image preprocessing and analysis. It includes:
- Importing essential libraries such as NumPy, Matplotlib, and OpenCV.
- Handling image datasets and applying preprocessing techniques.
- Integrating deep learning models or other algorithms for inference and visualization.

### 2. `Change_Detection_and_Edge_Detection.ipynb`
This notebook is dedicated to detecting changes and edges in images using various computer vision techniques:
- **Edge Detection**: Implements Canny, Sobel, or other filtering methods to detect edges.
- **Change Detection**: Uses image differencing and other algorithms to highlight differences between images.
- **Visualization**: Displays processed images to analyze detected changes and edges.

## Dependencies
To run these notebooks, ensure you have the following installed:
- Python (>=3.8)
- OpenCV (`cv2`)
- NumPy
- Matplotlib
- Jupyter Notebook

Install dependencies using:
```bash
pip install opencv-python numpy matplotlib jupyter
```

## Usage
1. Open a terminal and navigate to the project directory.
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open either `Main.ipynb` or `Change_Detection_and_Edge_Detection.ipynb` and run the cells sequentially.

## Applications
- Object tracking and monitoring
- Satellite image analysis
- Medical image processing
- Motion detection in videos

## Contribution
Feel free to contribute by improving algorithms, adding new techniques, or optimizing the existing implementation. Fork the repository, make changes, and submit a pull request.

## License
This project is licensed under the MIT License.

