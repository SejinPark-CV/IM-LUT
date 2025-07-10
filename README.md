# [ICCV'25] IM-LUT: Interpolation Mixing Look-Up Tables for Image Super-Resolution
### [IM-LUT: Interpolation Mixing Look-Up Tables for Image Super-Resolution](https://arxiv.org/pdf/xxx)
Sejin Park, Taehyung Lee, Kyong Hwan Jin, Seung-Won Jung, International Conference on Computer Vision (ICCV'25), Hawai'i, 2025

Our base code is from [LeRF](https://github.com/ddlee-cn/LeRF-PyTorch).

# Abstract

Super-resolution (SR) has been a pivotal task in image processing, aimed at enhancing image resolution across various applications. Recently, look-up table (LUT)-based approaches have attracted interest due to their efficiency and performance. However, these methods are typically designed for fixed scale factors, making them unsuitable for arbitrary-scale image SR (ASISR). Existing ASISR techniques often employ implicit neural representations, which come with considerable computational cost and memory demands. To address these limitations, we propose Interpolation Mixing LUT (IM-LUT), a novel framework that operates ASISR by learning to blend multiple interpolation functions to maximize their representational capacity. Specifically, we introduce IM-Net, a network trained to predict mixing weights for interpolation functions based on local image patterns and the target scale factor. To enhance efficiency of interpolation-based methods, IM-Net is transformed into IM-LUT, where LUTs are employed to replace computationally expensive operations, enabling lightweight and fast inference on CPUs while preserving reconstruction quality. Experimental results on several benchmark datasets demonstrate that IM-LUT consistently achieves a superior balance between image quality and efficiency compared to existing methods, highlighting its potential as a promising solution for resource-constrained applications.

<p align="center"><img src="[https://github.com/Vision-sejin/FDCNet/assets/117714660/1a6a6cdb-c98a-490e-abe3-3359e268391d/table.png](https://github.com/user-attachments/assets/8fa8ca83-110f-415f-9128-2300ba67bbed)"width="800" height="700"/>

# Code Details
updating...


