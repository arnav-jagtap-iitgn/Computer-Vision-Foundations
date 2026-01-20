## Gate 2 – Image Denoising, Feature Detection, and Matching

This module explores **noise removal and feature-based image understanding**,
building foundations for correspondence and recognition.

### Implemented Algorithms
- Noise generation: Gaussian noise and salt-and-pepper noise
- Denoising filters:
  - Mean filter
  - Median filter
  - Gaussian filter
  - Bilateral filter (implemented from scratch)
- Harris corner detection from scratch
- Patch-based feature descriptors
- Feature matching using Sum of Squared Differences (SSD)

### Evaluation
- Quantitative comparison using PSNR and SSIM
- Qualitative comparison of edge preservation and noise removal
- Detection of meaningful corners on clean images
- Localization of a key fragment within a noisy mosaic

### Key Observations
- Median filtering is most effective for salt-and-pepper noise
- Gaussian and bilateral filters perform well for Gaussian noise
- Harris corners distinguish edges and corners via eigenvalue structure
- SSD-based matching is simple but sensitive to scale, rotation, and illumination

### Concepts Learned
- Spatial filtering and noise models
- Structure tensor and corner response
- Feature descriptors and similarity metrics
- Limitations of simple patch-based matching
