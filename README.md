# Canny Edge Detection

This repository contains a Jupyter Notebook implementing **Canny Edge Detection** using OpenCV in Python. The Canny Edge Detection algorithm is a popular edge detection technique in computer vision, often used for object detection and image segmentation.

## 📌 Features

- Reads and displays an image
- Converts the image to grayscale
- Applies Gaussian Blur to reduce noise
- Uses Canny edge detection with adjustable thresholds
- Displays the final edge-detected image

## 🧪 Dependencies

## 🧪 Dependencies

To run this notebook, you need the following Python libraries:

- `opencv-python`
- `matplotlib`
- `numpy`
- `imutils`
- `easyocr`

Install them using pip:

```bash
pip install opencv-python
pip install matplotlib
pip install numpy
pip install imutils
pip install easyocr
```


## 📝 How to Run

1. Clone the repository or download the notebook file.
2. Open the notebook using Jupyter Notebook or JupyterLab.
3. Run the cells in sequence to see the image preprocessing and edge detection steps.
4. Adjust the threshold values in the Canny function to observe different edge results.

## 📷 Sample Workflow

1. Load image using `cv2.imread()`
2. Convert to grayscale using `cv2.cvtColor()`
3. Apply Gaussian blur using `cv2.GaussianBlur()`
4. Perform edge detection using `cv2.Canny()`
5. Display results using `matplotlib.pyplot`

## 🧠 Understanding Canny Edge Detection

The algorithm involves the following steps:

- **Noise Reduction**: Gaussian Blur
- **Gradient Calculation**: Sobel filters
- **Non-Maximum Suppression**: Thinning edges
- **Double Thresholding**: Edge categorization
- **Edge Tracking by Hysteresis**: Final edge selection

## 📂 Files

- `canny_edge_detection.ipynb` — Main notebook demonstrating the edge detection process for images.+
- `video_number_plate_detection.ipynb` — Main notebook demonstrating the edge detection process for videos.
- `different_number_plates.ipynb` — Main notebook demonstrating the edge detection process for different colour number plates.
- 
