# RSTSIC: Reparameterized Swin Transformer Stereo Image Compression

Official implementation of **RSTSIC: Reparameterized Swin Transformer Stereo Image Compression**

## 📌 Introduction

Stereo image compression faces challenges in effectively exploiting inter-view correlations due to occlusions and disparity variations. **RSTSIC** addresses these issues by:
- **Reparameterized Swin Block (RSB)**: Captures long-range dependencies via window-based self-attention while maintaining inference efficiency through structural reparameterization.
- **Cross Feature Enhancement Modules (CFEMs)**: Enables bidirectional feature interaction for inter-view redundancy reduction.

The framework achieves **58.57% fewer parameters** and **36.53% lower FLOPs** compared to SOTA models, making it ideal for real-time applications like autonomous driving and VR streaming.

## ✨ Key Features
- **High Efficiency**: Structural reparameterization reduces inference complexity without sacrificing performance.
- **State-of-the-Art Performance**: Outperforms HEVC, BPG, and learning-based models (DSIC, SASIC) on PSNR and MS-SSIM metrics.
- **Robust Generalization**: Validated on both urban (Cityscapes) and indoor (InStereo2K) stereo datasets.
- **Real-Time Ready**: Low latency (31.59s) and lightweight design (2.73M parameters).

## 🏗 Evaluation Results
![RD curves](figures/psnr_ms_ssim.png)

