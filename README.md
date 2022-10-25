# Learning 3D Human Pose and Shape Estimation Using Uncertainty-aware Human Part Segmentation

These are official codes for the framework of UPS in "Learning 3D Human Pose and Shape Estimation Using Uncertainty-aware Human Part Segmentation".

## Overall Architecture 

<img src="asserts\overview.png" alt="overview"  />

## Updates

`[2022/10/25]` More code will be released soon.

## Visualization

Qualitative comparison on 3DPW. From left to right: Input image, ROMP, PARE and UPS results.

<img src="asserts\visualization.png" alt="visualization" style="zoom: 50%;" />

## Requirements

UPS is a novel generalizable framework that can be easily embedded into other methods. Please install the following requirements before getting started.

- numpy
- opencv-python
- python>=3.6
- pyrender==0.1.45
- scipy==1.0.1
- smplx==0.1.13
- soft-renderer==1.0.0
- torch==1.6.0+cu101
- torchvision==0.7.0+cu101
- trimesh==3.9.35