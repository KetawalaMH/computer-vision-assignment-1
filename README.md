<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" class="logo" width="120"/>

## README

# EC7212 – Computer Vision and Image Processing

**Assignment 1: Image Processing Operations in Python (Google Colab)**

---

### Overview

This repository contains Python code (for Google Colab) that demonstrates basic image processing operations as required by the EC7212 Assignment 1. All tasks are performed on a user-supplied image, which is uploaded once and reused throughout.

---

### Tasks Implemented

1. **Reduce the Number of Intensity Levels in an Image**
    - The code reduces the grayscale intensity levels of an image to a user-specified number (e.g., 2, 4, 8, etc.).
2. **Spatial Averaging (Mean Filtering)**
    - Applies mean filters of sizes 3×3, 10×10, and 20×20 to the image to demonstrate image smoothing.
3. **Image Rotation**
    - Rotates the image by 45 and 90 degrees, displaying and saving the results.
4. **Block-wise Averaging (Simulated Spatial Resolution Reduction)**
    - Replaces each block of 3×3, 5×5, and 7×7 pixels with their average value to simulate reduced spatial resolution.

---

### How to Use

1. **Open the notebook in Google Colab.**
2. **Upload your image when prompted.**
    - The filename (e.g., `1.jpg`) will be used throughout the notebook.
3. **Run each code cell in order.**
    - Each cell processes the image for a specific task and displays the result.
4. **Download results as needed.**
    - Output images are saved and can be downloaded to your computer.

---

### Requirements

- Google Colab environment (no local setup required)
- Python 3.x
- Libraries: `opencv-python`, `numpy`, `matplotlib` (all available by default in Colab)

---

### File Structure

| File/Section | Description |
| :-- | :-- |
| `README.md` | This file |
| `1.jpg` | Example input image (user uploads their own) |
| `reduced_levels.jpg` | Output: Reduced intensity levels |
| `blur_3x3.jpg` | Output: 3×3 mean filtered image |
| `blur_10x10.jpg` | Output: 10×10 mean filtered image |
| `blur_20x20.jpg` | Output: 20×20 mean filtered image |
| `rotated_45.jpg` | Output: Image rotated by 45° |
| `rotated_90.jpg` | Output: Image rotated by 90° |
| `block_3x3.jpg` | Output: 3×3 block-wise averaged image |
| `block_5x5.jpg` | Output: 5×5 block-wise averaged image |
| `block_7x7.jpg` | Output: 7×7 block-wise averaged image |


---

### Notes

- Only one upload is needed; the same image is reused for all tasks.
- All image displays and processing are handled within the notebook.
- For any issues, check that the uploaded filename matches the one used in the code.

---

### Author

- [Your Name]
- EC7212 – Computer Vision and Image Processing

---

**End of README**

