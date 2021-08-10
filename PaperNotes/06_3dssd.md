### 00. Title
3DSSD: Point-based 3D Single Stage Object Detector

### 01. Authors
Zetong Yang (CUHK), Yannan Sun (HKUST), Shu Liu (CUHK), Jiaya Jia (CUHK)
### 02. Background
voxel-based single stage 3D detectors have poor performance, while point-based 2-stage 3D detectors are not efficient. point-based one-stage 3D detectors are underexplored.
### 03. Contributions
Outperforms SOTA voxel-based single stage methods by a large margin, has comparable performance to 2 stage point-based methods as well, with inference speed more than 25 FPS, 2x faster than 2 stage point-based methods.
### 04. Implementation Details
(1) discard upsampling and refinement layers

​    use Feature-FPS and Fusion sampling in downsampling process

(2) Use anchor-free framework to do 3D box regression

    * candidate generation layer
    * anchor free regression head
    * 3D center-ness assignment strategy

### 05. Questions
what's my questions

### 06. Further Reading

VoteNet, VoxelNet, SECOND, PointPillar, FPointNet, IPOD, PointRCNN