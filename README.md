# Cross-View Sparse Feature Matching via Geometry-Frequency Enhancement

## 📖 Abstract
Achieving reliable sparse local feature matching in cross-view scenes is essential for visual localization and robotic pose estimation. Existing sparse local feature matchers mainly rely on appearance-based descriptor interactions to establish correspondences. However, they often neglect geometric constraints and frequency-aware feature characteristics, making visually similar but geometrically inconsistent keypoints difficult to distinguish and increasing the risk of incorrect matches. To address these limitations, we propose GeoFNet, a geometry- and frequency-aware local feature matching framework consisting of two complementary modules. (a) The Local Geometry-Guided (LGG) module incorporates monocular depth-aware geometric cues into local descriptors by aligning geometric and appearance features in a shared latent space, allowing the matcher to distinguish visually similar but geometrically inconsistent keypoints. (b) The Spatial Frequency Enhancement (SFE) module captures complementary spatial and frequency characteristics through global context modeling and branch-specific frequency modulation, producing more discriminative descriptors for reliable correspondence estimation. Experiments on HPatches and ScanNet-1500 demonstrate that GeoFNet achieves superior homography estimation and relative pose estimation performance compared with state-of-the-art approaches.

## TODO List

- [ ] release the training code
