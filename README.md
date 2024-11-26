# Feature Detection and Perspective Transformation using Homography

This project demonstrates the use of feature detection, matching, and homography estimation for perspective transformation of an image.

---

## Features
- Detects keypoints and descriptors using ORB.
- Matches features between two images using the BFMatcher.
- Computes a homography matrix to align the source image to the target image.
- Warps the source image to match the perspective of the target image.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/feature_detection_homography.git
   cd feature_detection_homography
2. Install dependencies:
   ``` bash
   pip install -r requirements.txt
3. Place two images in the input_images/ folder:
   ``` bash
   source.jpg: The source image.
   target.jpg: The target image.
4. Run the script:
   ``` bash
   python feature_matching_homography.py
