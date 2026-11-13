# ProtoTrust: Proposal-Level Foundation Guidance for Reliable Unsupervised Domain-Adaptive Object Detection

Official repository for **ProtoTrust**, a teacher–student framework for unsupervised domain-adaptive object detection (DAOD).

ProtoTrust improves target-domain detection through two complementary mechanisms:

- **Prototype-based pseudo-label filtering:** Uses a nearest-neighbor classifier with source foreground and background prototypes extracted from frozen DINOv3 representations to improve the reliability of teacher-generated pseudo-labels.
- **Decision-Centric Distillation (DCD):** Transfers foundation-model knowledge to the detector within accepted and prototype-rejected regions, rather than aligning entire feature maps.

Both components are used exclusively during training, leaving the inference detector unchanged.

## Results

ProtoTrust achieves state-of-the-art performance on five DAOD benchmarks:

- Pascal VOC → Clipart, Comic, and Watercolor
- Cityscapes → Foggy Cityscapes
- Cityscapes → BDD100K

## Code Availability

**The code is not yet publicly available.**

The implementation, configuration files, and instructions for reproducing the experiments will be released after the paper review process.

## Paper

Paper currently under review. Further details will be provided following the review process.
