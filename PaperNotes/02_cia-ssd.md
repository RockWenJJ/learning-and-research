### 00. Title
CIA-SSD: Confident IoU-Aware Single-Stage Object Detector From Point Cloud
### 01. Authors
Wu Zheng, Weiliang Tang, Sijin Chen, Li Jiang, Chi-Wing Fu
### 02. Background
current single-stage detectors for 3D points objects often treat object localization and category classification as separate tasks, so the localization accuracy and classification confidence often misalign.
### 03. Contributions
(1) design the lightweight spatial-semantic feature aggregation module

(2) the predicted confidence is rectified with designed IoU-aware confidence rectification module

(3) formulate the distance-variant IoU-weighted NMS to obtain smoother regression and avoid redundant predictions.

To sum up, it achieves top performance in KITTI test set.

### 04. Implementation Details
(1) point cloud encoder: voxelize, use SPConvNet

(2) Spatial-Semantic Feature Aggregation

(3) IoU-Aware Confidence Rectification: the IoUs predicted with anchors are rather discriminative

(4) Distance-variant IoU-weighted NMS for post-processing the predictions.

### 05. Questions
Details about Distance-variant IoU-weighted NMS

### 06. Other relative papers

[SASSD](https://openaccess.thecvf.com/content_CVPR_2020/papers/He_Structure_Aware_Single-Stage_3D_Object_Detection_From_Point_Cloud_CVPR_2020_paper.pdf)

[3DSSD](https://arxiv.org/abs/2002.10187)

[Sparse Convolutional Neural Networks](https://openaccess.thecvf.com/content_cvpr_2015/papers/Liu_Sparse_Convolutional_Neural_2015_CVPR_paper.pdf)