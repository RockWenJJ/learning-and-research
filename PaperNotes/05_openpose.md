### 00. Title
OpenPose: Realtime Multi-Person 2D Pose Estimation using Part Affinity Fields

### 01. Authors

Zhe Cao, Tomous Simon, Shih-En Wei, Yaser Sheikh (Berkeley Artificial Intelligence Research Lab, BAIR)
### 02. Background

Previous work on multiple people's pose detection is too slow.

### 03. Contributions
Present a realtime approach to detect 2D pose of multiple people in an image.
### 04. Implementation Details
(1) iteratively predicts affinity fields and detection confidence maps (predicts PAFs first, then predicts confidence map);

(2) apply a loss function at the end of each stage, which could address the vanishing gradient problem;

(3) use L2 loss between the estimated predictions and the groundtruth maps and fields.

(4) use Hungarian algorithm to obtain optimal matching.

### 05. Questions
what's my questions

### 06. Further Reading