## Gate 1 – Low-Rank Representation and Background Separation

This module focuses on understanding image and video data through
**linear algebra and low-rank representations**.

### Implemented Algorithms
- Singular Value Decomposition (SVD) implemented from scratch using eigen-decomposition
- Image compression using top-k singular values
- Reconstruction error analysis using Mean Squared Error (MSE)
- Background–foreground separation in videos using low-rank approximation

### Key Ideas
- Natural images and videos often lie in a low-dimensional subspace
- Dominant singular values capture global structure, while smaller ones capture noise or motion
- Background in videos is typically low-rank, while moving objects form sparse/high-rank components

### Results
- Demonstrated trade-off between compression ratio and reconstruction quality
- Successfully removed moving objects (cars) from a video by reconstructing with few singular values
- Visualized background-only and foreground-only components

### Concepts Learned
- Linear algebra in vision
- Best rank-k approximation
- Relationship between SVD, compression, and denoising
