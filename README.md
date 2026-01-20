# Foundations of Computer Vision: Geometry, Motion & Reconstruction

This repository contains implementations of classical computer vision algorithms
developed as part of the ES666 Computer Vision course.

Each module was implemented with a focus on mathematical understanding, avoiding
high-level library shortcuts where possible.

## Project Modules

### Gate 1 – Low-Rank Representation
- Singular Value Decomposition (SVD) from scratch
- Image compression using top-k singular values
- Background–foreground separation in videos

### Gate 2 – Feature Detection & Denoising
- Gaussian, median, mean, and bilateral filtering
- Harris corner detection from scratch
- Patch-based feature descriptors and SSD matching

### Gate 3 – Geometry & Image Stitching
- Inverse warping from scratch
- Homography estimation using RANSAC
- Multi-image stitching into a reference plane

### Gate 4 – Motion Estimation
- Lucas–Kanade optical flow from scratch
- Optical-flow-based backward warping
- Bit-plane image analysis

## Tools
Python, NumPy, SciPy, OpenCV, Matplotlib
