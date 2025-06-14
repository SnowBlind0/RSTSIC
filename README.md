# RSTSIC: Reparameterized Swin Transformer Stereo Image Compression

Official implementation of **RSTSIC: Reparameterized Swin Transformer Stereo Image Compression**

##  Key Features
- **State-of-the-Art Performance**: Outperforms traditional codecs and learning-based compression methods on PSNR and MS-SSIM metrics.
- **High Efficiency**: Structural reparameterization reduces inference complexity without sacrificing performance.
- **Robust Generalization**: Validated on both urban (Cityscapes) and indoor (InStereo2K) stereo datasets.
- **Real-Time Ready**: Low latency and lightweight design.

##  Evaluation Results


## Qualitative Results
<table>
  <tr>
    <td>
      <div style="text-align: center">
        <img src="figures/ori_rec.png" width="100%" alt="Ground Truth">
        <p><strong>Ground Truth</strong></p>
      </div>
    </td>
    <td>
      <div style="text-align: center">
        <img src="figures/RSTSIC_rec.png" width="90%" alt="RSTSIC">
        <p><strong>RSTSIC</strong> bpp=0.043, PSNR=33.8</p>
      </div>
    </td>
    <td>
      <div style="text-align: center">
        <img src="figures/LDMIC_rec.png" width="90%" alt="LDMIC">
        <p><strong>LDMIC</strong> bpp=0.045, PSNR=33.4</p>
      </div>
    </td>
    <td>
      <div style="text-align: center">
        <img src="figures/SASIC_rec.png" width="90%" alt="SASIC">
        <p><strong>SASIC</strong> bpp=0.052, PSNR=32.8</p>
      </div>
    </td>
  </tr>
</table>

## Environment Configuration
Our code was tested with the following environment configurations. It may work with other versions.

- Ubuntu 20.04
- NVIDIA Tesla T4 GPU
- CUDA 12.4
- Python 3.9
- PyTorch 2.1.0 + cu121
- CompressAI 1.2.0

## Ackownledgement
Our code is based on the implementation of [CompressAI](https://github.com/InterDigitalInc/CompressAI). We thank the authors for open-sourcing their code.
