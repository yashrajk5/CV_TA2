# 🔍 Feature Detection & Matching in Images (SIFT, ORB, RANSAC)

This project demonstrates how to detect and match keypoints between two images using popular computer vision algorithms — SIFT, ORB (alternative to SURF), and RANSAC for outlier rejection and transformation estimation.

---

## 📁 Files Included

| File Name           | Description |
|---------------------|-------------|
| `SHIFT_TA2_65.ipynb`  | Keypoint detection and matching using SIFT. |
| `SURF_TA2_65.ipynb`   | Robust feature detection using ORB (free alternative to SURF). |
| `RANSAC_TA2_65.ipynb` | Uses RANSAC to filter keypoint matches and estimate a homography matrix. |

---

## 📸 Sample Images

Use sample images from OpenCV like:
- [`box.png`](https://github.com/opencv/opencv/blob/master/samples/data/box.png)
- [`box_in_scene.png`](https://github.com/opencv/opencv/blob/master/samples/data/box_in_scene.png)

Or split a single side-by-side photo into two halves.

---

## 🧠 Algorithms Used

### 1. SIFT (Scale-Invariant Feature Transform)
- Detects keypoints that are invariant to scale and rotation.
- Matched using BFMatcher with L2 norm.

### 2. ORB (Oriented FAST and Rotated BRIEF)
- Free alternative to SURF.
- Efficient and suitable for real-time applications.
- Uses Hamming distance for descriptor matching.

### 3. RANSAC (Random Sample Consensus)
- Filters out incorrect keypoint matches.
- Estimates a homography matrix between image pairs.

---

## ⚙️ Requirements

Install dependencies using pip:

```bash
pip install opencv-python matplotlib
