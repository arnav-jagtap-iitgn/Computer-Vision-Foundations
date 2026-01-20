## Gate 3 – Projective Geometry and Image Stitching

This module focuses on **geometric vision**, covering coordinate transformations,
robust estimation, and multi-image alignment.

### Implemented Algorithms
- Forward and inverse image warping from scratch
- Homography-based image transformation
- Feature detection using SIFT (OpenCV)
- Feature matching with ratio test
- Homography estimation using:
  - Direct Linear Transform (DLT)
  - RANSAC implemented from scratch
- Multi-image stitching into a common reference plane

### Key Design Choices
- Used inverse warping to avoid holes and ensure complete output images
- Fixed the reference image to preserve geometric consistency
- Used RANSAC to handle outliers in feature matching

### Results
- Successfully restored warped image regions into a common plane
- Robust alignment despite noisy or incorrect matches
- Clean stitched outputs without geometric distortion

### Concepts Learned
- Projective geometry and homogeneous coordinates
- Outlier rejection and robust estimation
- Importance of reference frames in stitching
- Relationship between feature matching and geometric alignment
