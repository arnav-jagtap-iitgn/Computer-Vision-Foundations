## Gate 4 – Motion Estimation and Optical Flow

This module explores **temporal vision**, focusing on pixel-level motion estimation
and motion-based image reconstruction.

### Implemented Algorithms
- Dense Lucas–Kanade optical flow from scratch
- Image gradient computation using convolution kernels
- Least-squares solution for motion vectors in local windows
- Dense flow visualization using arrow plots
- Optical-flow-based backward warping
- Bilinear interpolation implemented manually
- Motion compensation quality evaluation using PSNR
- Bit-plane analysis for hidden message decoding

### Key Observations
- Smooth and consistent flow indicates global or slow motion
- Diverging or swirling flow indicates multiple or complex motions
- Backward warping avoids holes and overlapping artifacts
- Optical flow accuracy depends on texture and brightness constancy

### Results
- Visualized motion patterns across multiple video sequences
- Successfully warped earlier frames to align with later frames
- Quantitatively evaluated warping quality

### Concepts Learned
- Brightness constancy assumption
- Optical flow constraints and limitations
- Forward vs backward warping
- Role of motion estimation in video understanding
