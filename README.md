# GeoFNet: Geometry-Frequency Enhancement for Sparse Feature Matching

## 📖 Abstract
Sparse feature matching is fundamental to robot visual localization and mapping. Existing methods mainly rely on appearance-based descriptor interactions to establish correspondences. However, appearance cues alone can struggle to distinguish visually similar keypoints with inconsistent geometric structures, leading to incorrect correspondences. To address this limitation, we propose GeoFNet, a geometry- and frequency-aware local feature matching framework consisting of two complementary modules. First, the Local Geometry-Guided (LGG) module incorporates monocular depth-derived geometric cues into local descriptors by aligning geometric and appearance features in a shared latent space, enabling more reliable discrimination of geometrically inconsistent keypoints. Second, the Spatial Frequency Enhancement (SFE) module combines global context modeling with branch-specific frequency modulation to capture complementary structural and fine-grained information, producing more discriminative descriptors for correspondence estimation. Experiments on HPatches and ScanNet-1500 demonstrate that GeoFNet achieves superior performance in homography estimation and relative pose estimation compared with state-of-the-art approaches.

## TODO List

- [ ] release the training code
- [ ] release model weights
