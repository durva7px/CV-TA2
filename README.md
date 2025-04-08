# CV-TA2
SIFT, RANSAC, Harris Corner Detection in OpenCV

# Computer Vision Feature Detection Assignment

This repository contains implementations of classical feature detection and matching algorithms using OpenCV in Python. The Jupyter Notebook includes:

## Implemented Algorithms

### 1. SIFT (Scale-Invariant Feature Transform)
- Detect and match keypoints between two images.
- Visualizes effects of changing parameters like `contrastThreshold`, `edgeThreshold`.

### 2. RANSAC (Random Sample Consensus)
- Removes outlier keypoint matches from SIFT using homography estimation.
- Helps robustly fit a geometric transformation between image pairs.

### 3. Harris Corner Detector
- Identifies corners in a grayscale image.
- Shows effect of different parameters like `blockSize`, `ksize`, and `k`.

## 🔧 Technologies Used
- Python 3
- OpenCV (cv2)
- Matplotlib
- NumPy
- Jupyter Notebook
