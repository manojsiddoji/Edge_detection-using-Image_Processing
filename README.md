# Lane Line Detection Using Image Processing 🛣️

## Introduction
This project implements lane line detection using image processing techniques. 
The workflow involves several key steps, including color selection, gray scaling, Gaussian smoothing, edge detection, and the Hough transform to detect lane lines on the road. 
The process can handle both images and video feeds, making it adaptable to real-time applications such as autonomous driving systems.

## Workflow Diagram ☕
![edge detection workflow](https://github.com/user-attachments/assets/015d480b-4fbb-4091-99b0-1736d0476fa9)

## Workflow Overview 📝
### 1. Color Selection:
Choose the appropriate color space (RGB, HSV, or HSL) for lane detection.
### 2. Gray Scaling:
Convert the image to grayscale to reduce complexity.
### 3. Gaussian Smoothing:
Apply Gaussian filtering to reduce noise in the image.
### 4. Edge Detection: 
Use the Canny edge detection method to identify the edges of lane lines.
### 5. Region of Interest: 
Define the region of interest to focus on the lane area.
### 6. Hough Transform:
Detect lines in the edge-detected image using the Hough transform.
### 7. Averaging and Extrapolating:
Refine the detected lane lines for clear output.

## Requirements 🧑‍💻
- Python 3.x
- Jupyter Notebook
- OpenCV (cv2)
- NumPy
- Matplotlib
- Moviepy

## Installation 📩
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/manojsiddoji/Edge_detection-using-Image_Processing.git
2. Navigate to the project directory:
   ```bash
   cd Edge_detection-using-Image_Processing
3. Install the required Python packages:
   ```bash
   pip install [all the requirements]
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
5. Open the `Final.ipynb` file from the Jupyter interface to run the lane line detection workflow step-by-step.
---
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

   
