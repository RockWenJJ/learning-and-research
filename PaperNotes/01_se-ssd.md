### SE-SSD:  Self-Ensembling Single-Stage Object Dector From Point Cloud
### 01. Authors
Wu Zheng, WeiliangTang, Li Jiang, Chi-Wing Fu

research interests: point cloud processing and 3D vision, user ineraction and data visualization

### 02. Background
current single-stage detectors for point clouds is either with low frequency or low fps.
### 03. Contributions

Attains top performance in KITTI BEV and 3D leaderboards with an ultra-high inference speed.

### 04. Implementation Details
1. inspired by knowledge distilling, using a pair of teacher and student SSDs.
2. treat the relative more precise teacher predictions as soft targets and employ them to jointly optimize the student with hard targets.
3. propose an orientation-aware distance-iou loss (ODIOU, for 0, pi, -pi, the loss is small).
4. propose an shape-aware data augmentation method (a plug-and-play module).

### 05. Questions
what's my questions

### 06. Extra Reading

[PV-RCNN](https://arxiv.org/abs/1912.13192)

[TANet](https://arxiv.org/abs/1912.05163)

[Point-GNN](https://arxiv.org/abs/2003.01251)