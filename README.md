# UVE-Net

# UVEB: A Large-scale Benchmark and Baseline Towards Real-World Underwater Video Enhancement

<hr />

> **Abstract**: *Learning-based underwater image enhancement (UIE) methods have made great progress. However, the lack of large-scale and high-quality paired training samples has become the main bottleneck hindering the development of UIE. The inter-frame information in underwater videos can accelerate or optimize the UIE process. Thus, we constructed the first large-scale high-resolution underwater video enhancement benchmark (UVEB) to promote the development of underwater vision. UVEB is 500 times larger than the existing underwater image enhancement benchmark. It contains 1,308 pairs of video sequences and more than 453,000 high-resolution with 38\% Ultra-High-Definition (UHD) 4K frame pairs. UVEB comes from multiple countries, containing various scenes and video degradation types to adapt to diverse and complex underwater environments. We also propose the first supervised underwater video enhancement method, UVE-Net. UVE-Net converts the current frame information into convolutional kernels and passes them to adjacent frames for efficient inter-frame information exchange. By fully utilizing the redundant degraded information of underwater videos, UVE-Net completes video enhancement better. Experiments show the effective network design and good performance of UVE-Net.*
<hr />

This repository is the official PyTorch implementation of our CVPR2024 paper "UVEB: A Large-scale Benchmark and Baseline Towards Real-World Underwater Video Enhancement".

## Network Architecture
![Architecture](https://github.com/ck324/ck324.github.io/assets/116191412/a168aec1-6a8e-41b0-8160-fd0304f6e2a8)

## Updates
[2024-02-27] Paper has been accepted by CVPR2024\
[2024-03-25] Training & Testing code is available!

## Experimental Results
Quantitative comparisons of enhanced video quality on UVEB dataset. In the Memory column, ∗ represents the CPU, while without ∗ represents the GPU. Top 1st, 2nd results are marked in red and blue respectively.
<img width="467" alt="quantitative" src="https://github.com/ck324/ck324.github.io/assets/116191412/165d8c28-b878-4986-8b5d-90884b3d31ca">

Ablation studies of major components in UVE-Net.
<img width="467" alt="ablation" src="https://github.com/ck324/ck324.github.io/assets/116191412/613af18b-12df-4403-929b-3546ada451ec">


## Dependencies

## Get Started




## Citation
