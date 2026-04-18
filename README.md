KeyVisNet: A Disambiguative Monocular Pose Estimation Network Based on Keypoint Visibility Perception for Non-cooperative Spacecraft
### Dataset Download Link
Download the Symmetric Ambiguity Spacecraft Dataset (SASD) from: https://zenodo.org/uploads/19638818
Note: If the link fails to access, please check the network connection or try again later (current link shows "web page parsing failed", which may be a temporary access issue).
###📦 Symmetric Ambiguity Spacecraft Dataset (SASD)
###📖 Overview
Symmetric Ambiguity Spacecraft Dataset (SASD) is a synthetic dataset designed for monocular pose estimation of non-cooperative spacecraft. It is built based on the publicly available 3D model of the Symmetric Ambiguity Spacecraft Dataset (SASD) from NASA.
Compared with existing datasets such as SPEED, SASD provides richer and more comprehensive supervision, including:
- 2D semantic keypoints  
- Keypoint visibility labels
- Geometrically consistent annotations  
This makes SASD particularly suitable for keypoint-based pose estimation, learnable PnP frameworks, and multi-task learning.
---
📷 Camera Sampling Strategy
Sampling ranges:
- Azimuth angle: [0°, 360°]  
- Elevation angle: [-75°, 75°]  
- Distance: 100 m – 600 m

Spherical spatial distribution of sampled camera poses in the training set.
---
🔑 Keypoint Definition
A set of semantic 3D keypoints is predefined on the spacecraft model:
- Distributed across the main body and solar panels  
- Includes symmetric structures for ambiguity analysis 
- Defined in the local coordinate system for cross-sample consistency 

Spatial layout and visibility of predefined keypoints on the FGST spacecraft. Left：Front view; Right：Back view.
---
📊 Dataset Statistics
- Total images: 10,500  
- Training set: 10,000  
- Test set: 500  
- Resolution: 1920 × 1200  
- Camera parameters (aligned with SPEED dataset):
Parameter
Description
Value
Nu
Image width (pixels)
1920
Nv
Image height (pixels)
1200
fx
Focal length (horizontal)
0.0172 m
fy
Focal length (vertical)
0.0172 m
Px
Pixel size (horizontal)
5.86 µm
Py
Pixel size (vertical)
5.86 µm
---
