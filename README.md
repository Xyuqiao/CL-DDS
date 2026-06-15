# Continual Learning with Dynamic Domain Shifts

Official implementation of the paper published at ICME 2026: ''**Continual Learning with Dynamic Domain Shifts**''

## Code Release Plan
The code will be publicly released soon.

## Abstract
Standard continual learning (CL) benchmarks often overlook the severe continually distribution shifts and class imbalance prevalent in real-world scenarios. In this paper, we introduce continual learning with dynamic domain shifts (CL-DDS), a realistic setting where domains naturally alternate while retaining inherent distribution characteristics. This imposes dual challenges: catastrophic forgetting and dynamic distribution shifts. Empirically, we find existing methods exhibit significant instability in CL-DDS. Consequently, we propose a novel plug-and-play method to enhance model discriminability and stability. We first introduce an adaptive hierarchical calibration (AHC) module based on the effective number of samples to mitigate margin biases caused by dynamic distribution shifts and imbalance. Additionally, a domain knowledge stabilization (DKS) strategy is designed to enhance the model to simultaneously accommodate the batch normalization statistics of previous tasks and those of the current task. Extensive experiments demonstrate that our method consistently improves the performance of existing CL methods across CL-DDS scenarios.

