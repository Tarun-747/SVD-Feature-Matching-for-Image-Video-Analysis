# Visioneers: SVD & Feature Matching for Image & Video Analysis

**Technologies:** Python, NumPy, OpenCV, scikit-image, Matplotlib  

This project demonstrates hands-on applications of **Singular Value Decomposition (SVD)** and **feature matching** in computer vision. It was inspired by course assignments where noisy and corrupted images/videos were restored, analyzed, and reconstructed.

---

## Project Overview

1. **Image Compression & Reconstruction**
   - Implemented SVD from scratch using eigen-decomposition.
   - Reconstructed images using top-k singular values, achieving **~90% compression** while retaining **>95% SSIM**.

2. **Video Background-Foreground Separation**
   - Applied low-rank approximation on video frames to separate static background from moving objects.
   - Reduced dynamic noise by **~85%**, effectively removing moving cars from static scenes.

3. **Image Denoising & Filtering**
   - Implemented Mean, Median, Gaussian, and Bilateral filters.
   - Evaluated performance on Gaussian and Salt-Pepper noise with PSNR improvement up to **+12 dB**.

4. **Feature Detection & Matching**
   - Extracted **>500 keypoints** from images using Harris corner detection.
   - Matched features using patch-based descriptors and SSD, achieving **~80% matching accuracy** in noisy mosaics.

---

