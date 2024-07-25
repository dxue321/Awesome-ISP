<!-- The superlink doesn't support uppercases -->
# Awesome Image Signal Processing

A collection of Image Signal Processing papers.

## Contents

- [Demosaicing](#Demosaicing)
- [White Balance](#White-balanc)
- [Tone mapping](#Tone-mapping)
- [Gamut mapping](#Gamut-mapping)
- [Image retouching](#Image-retouching)
- [End-to-end ISP](#End-to-end-ISP)
- [Raw image reconstruction](#Raw-image-reconstruction)


 <!-- Template: - **Title, *TPAMI 2020***\
[[Paper]()]
[[Project]()]
[[Code]()]--> 

## Review & Tutorial

- ⭐ **Mobile Computational Photography: A Tour, *arXiv 2021***\
[[Paper](https://arxiv.org/abs/2102.09000)]

- ⭐ **Understanding the in-camera rendering pipeline & the role of AI and deep learning, *ICCV 2023 Tutorial***\
[[Slides](https://arxiv.org/abs/2102.09000](https://www.eecs.yorku.ca/~mbrown/ICCV2023_For_Print.pdf))]

- ⭐ **Camera Processing Pipeline, *lecture***\
[[Slides](https://web.stanford.edu/class/cs231m/lectures/lecture-11-camera-isp.pdf))]


## Gamut mapping

- **Gamut Extension for Cinema, *TIP 2017***\
[[Paper](https://www.jvazquez-corral.net/GamutExtension.pdf)]

- **Vision Models for Wide Color Gamut Imaging in Cinema, *TPAMI 2021***\
[[Paper](https://ueaeprints.uea.ac.uk/id/eprint/80856/1/Vision_Models_for_Wide_Color_Gamut_Imaging_in_Cinema.pdf)]

- **Improving Color Space Conversion for Camera-Captured Images via Wide-Gamut Metadata, *CIC 2020***\
[[Paper](https://drive.google.com/file/d/1vjXx5UQazxWY2h6RTcKRp2XzGvJt-Gcz/view)]
[[Code](https://github.com/hminle/improving-color-space-conversion-via-metadata)]

- **GamutMLP: A Lightweight MLP for Color Loss Recovery, *CVPR 2024*** \
[[Paper](https://arxiv.org/abs/2304.11743)]
[[Project](https://gamut-mlp.github.io/)]
[[Code](https://github.com/hminle/gamut-mlp)]

- **GamutNet: Restoring Wide-Gamut Colors for Camera-Captured Images, *CIC 2022*** \
[[Paper](https://library.imaging.org/admin/apis/public/api/ist/website/downloadArticle/cic/29/1/art00003)]
[[Code](https://github.com/gamut-mapping/GamutNet)]


## Tone mapping


## Image retouching

- **Deep Photo Enhancer: Unpaired Learning for Image Enhancement from Photographs with GANs, *CVPR 2018***\
[[Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_Deep_Photo_Enhancer_CVPR_2018_paper.pdf)]
[[Code](https://github.com/nothinglo/Deep-Photo-Enhancer)]

- **Underexposed Photo Enhancement using Deep Illumination Estimation, *CVPR 2019***\
[[Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Underexposed_Photo_Enhancement_Using_Deep_Illumination_Estimation_CVPR_2019_paper.pdf)]
[[Code](https://github.com/dvlab-research/DeepUPE)]

### 3DLUT

- **Learning Image-adaptive 3D Lookup Tables for High Performance Photo Enhancement in Real-time, *TPAMI 2020*** \
[[Paper](https://arxiv.org/abs/2009.14468)]
[[Code](https://github.com/HuiZeng/Image-Adaptive-3DLUT)]

- **AdaInt: Learning Adaptive Intervals for 3D Lookup Tables on Real-time Image Enhancement, *CVPR 2022*** \
[[Paper](https://arxiv.org/abs/2204.13983)]
[[Code](https://github.com/ImCharlesY/AdaInt)]

- **4D LUT: Learnable Context-Aware 4D Lookup Table for Image Enhancement, *TIP 2023*** \
[[Paper](https://arxiv.org/abs/2209.01749)]
[[Code](https://github.com/ChengxuLiu/4DLUT)]

- **Learning Pixel-Adaptive Weights for Portrait Photo Retouching** \
[[Paper](https://arxiv.org/abs/2112.03536)]
[[Code](https://github.com/CodeMonsterPHD/PWA)]

- **CLUT-Net: Learning Adaptively Compressed Representations of 3DLUTs for Lightweight Image Enhancement, *ACMMM 2022*** \
[[Paper](https://dl.acm.org/doi/10.1145/3503161.3547879)]
[[Code](https://github.com/Xian-Bei/CLUT)]

- **Adaptively Hashing 3DLUTs for Lightweight Real-time Image Enhancement, *ICME 2023*** \
[[Paper](https://ieeexplore.ieee.org/document/10220002)]
[[Code](https://github.com/Xian-Bei/CLUT)]

- **NILUT: Conditional Neural Implicit 3D Lookup Tables for Image Enhancement, *AAAI 2024*** \
[[Paper](https://arxiv.org/pdf/2306.11920)]
[[Code](https://github.com/mv-lab/nilut)]

- **Taming Lookup Tables for Efficient Image Retouching, *ECCV 2024*** \
[[Paper](https://arxiv.org/abs/2403.19238)]
[[Code](https://github.com/Stephen0808/ICELUT)]


### Tone curving

- **CURL: Neural Curve Layers for Global Image Enhancement, *ICPR 2020***\
[[Paper](https://arxiv.org/abs/1911.13175)]
[[Code](https://github.com/sjmoran/CURL)]

- **Multi-Curve Translator for High-Resolution Photorealistic Image Translation, *ECCV 2022***\
[[Paper](https://arxiv.org/abs/2203.07756)]

- **FlexiCurve: Flexible Piecewise Curves Estimation for Photo Retouching, *CVPRW 2023***\
[[Paper](https://openaccess.thecvf.com/content/CVPR2023W/NTIRE/papers/Li_FlexiCurve_Flexible_Piecewise_Curves_Estimation_for_Photo_Retouching_CVPRW_2023_paper.pdf)]
[[Project](https://li-chongyi.github.io/FlexiCurve/)]
[[Code]()]

- **NamedCurves: Learned Image Enhancement via Color Naming, *ECCV 2024***\
[[Paper](https://arxiv.org/pdf/2407.09892)]
[[Project](https://namedcurves.github.io/)]
[[Code](https://github.com/davidserra9/namedcurves)]


### Filter

- **DeepLPF: Deep Local Parametric Filters for Image Enhancement, *CVPR 2020***\
[[Paper](https://arxiv.org/pdf/2003.13985)]
[[Code](https://github.com/sjmoran/DeepLPF)]

## Raw image reconstruction

- **Spatially Aware Metadata for Raw Reconstruction, *WACV 2021***\
[[Paper](https://openaccess.thecvf.com/content/WACV2021/papers/Punnappurath_Spatially_Aware_Metadata_for_Raw_Reconstruction_WACV_2021_paper.pdf)]

- **Learning sRGB-to-Raw-RGB De-rendering with Content-Aware Metadata, *CVPR 2022***\
[[Paper](https://arxiv.org/abs/2206.01813v1)]
[[Code](https://github.com/SamsungLabs/content-aware-metadata)]

- **Raw Image Reconstruction with Learned Compact Metadata, *CVPR 2023***\
[[Paper](https://arxiv.org/abs/2302.12995)]
[[Code](https://github.com/wyf0912/R2LCM)]

- **Metadata-Based RAW Reconstruction via Implicit Neural Functions, *CVPR 2023***\
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Metadata-Based_RAW_Reconstruction_via_Implicit_Neural_Functions_CVPR_2023_paper.pdf)]

 <!-- Template: - **Title, *TPAMI 2020***\
[[Paper]()]
[[Project]()]
[[Code]()]--> 

## End-to-end ISP

- **CameraNet: A Two-Stage Framework for Effective Camera ISP Learning, *TIP 2021***\
[[Paper](https://arxiv.org/abs/1908.01481)]
[[Code](https://github.com/zhetongliang/CameraNet_official)]

- **AWNet: Attentive Wavelet Network for Image ISP, *ECCVW 2020***\
[[Paper](https://arxiv.org/abs/2008.09228)]
[[Code](https://github.com/Charlie0215/AWNet-Attentive-Wavelet-Network-for-Image-ISP)]

- **PyNET-CA: Enhanced PyNET with Channel Attention for End-to-End Mobile Image Signal Processing, *ECCV 2020 AIM workshop***\
[[Paper](https://arxiv.org/abs/2104.02895)]
[[Code](https://github.com/egyptdj/skyb-aim2020-public)]

- **CSANet: High Speed Channel Spatial Attention Network for Mobile ISP, *CVPRW 2021***\
[[Paper](https://openaccess.thecvf.com/content/CVPR2021W/MAI/papers/Hsyu_CSAnet_High_Speed_Channel_Spatial_Attention_Network_for_Mobile_ISP_CVPRW_2021_paper.pdf)]

- **CIE XYZ Net: Unprocessing Images for Low-Level Computer Vision Tasks, *TPAMI 2020***\
[[Paper](https://arxiv.org/abs/2006.12709)]
[[Code](https://github.com/mahmoudnafifi/CIE_XYZ_NET)]

- **CycleISP: Real Image Restoration via Improved Data Synthesis, *TPAMI 2020***\
[[Paper](https://arxiv.org/abs/2003.07761)]
[[Code](https://github.com/swz30/CycleISP)]

- **RAWtoBit: A Fully End-to-end Camera ISP Network, *ECCV 2022***\
[[Paper](https://arxiv.org/abs/2208.07639)]

- **Model-Based Image Signal Processors via Learnable Dictionaries, *AAAI 2022***\
[[Paper](https://arxiv.org/abs/2201.03210)]
[[Code](https://github.com/mv-lab/AISP?tab=readme-ov-file)]

- **Self-Supervised Reversed Image Signal Processing via Reference-Guided Dynamic Parameter Selection, *arXiv 2023***\
[[Paper](https://arxiv.org/abs/2303.13916)]

- **ParamISP: Learned Forward and Inverse ISPs using Camera Parameters, *CVPR 2024***\
[[Paper](https://arxiv.org/abs/2312.13313)]
[[Project](https://woo525.github.io/ParamISP/)]
[[Code](https://github.com/woo525/ParamISP)]

- **Rawformer: Unpaired Raw-to-Raw Translation for Learnable Camera ISPs, *ECCV 2024***\
[[Paper](https://arxiv.org/abs/2404.10700)]
[[Code](https://github.com/gosha20777/rawformer)]

- **MetaISP – Exploiting Global Scene Structure for Accurate Multi-Device Color Rendition, *VMV 2023***\
[[Paper](https://arxiv.org/pdf/2401.03220)]
[[Code](https://github.com/vccimaging/MetaISP)]



## Demosaicing

## White Balance








