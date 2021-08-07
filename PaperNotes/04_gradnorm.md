### 00. Title
GradNorm: Gradient Normalization for Adaptive Loss Balancing in Deep Multitask Networks
### 01. Authors
Zhao Chen, VIjay Badrinarayanan, Chen-Yu Lee, Andrew Rabinovich, @Magic Leap
### 02. Background
Although deep multitask networks offer better speed and performance for single-task counterparts, it's challenging to train the network. Current grid search method to balance various tasks is tedious.
### 03. Contributions
Present a gradient normalization algorithm that automatically balances training by dynamically tuning gradient magnitutes. It boosts network performance while significantly curtailing overfitting.
### 04. Implementation Details
(1)  The common scale for gradients is the average gradient norm

(2) The relative inverse training rate of task i, r_i(t) can be used to rate balance the gradients,

(3) GradNorm is then implemented as an L1 loss function L_grad between the actual and target gradient norms at each timestep for each task, summed over all tasks.

### 05. Questions
what's my questions

### 06. Further Reading