# Unveiling Hidden Details: A RAW Data-Enhanced Paradigm for Real-World Super-Resolution

[![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)]([https://arxiv.org/abs/2408.11758](https://arxiv.org/abs/2405.07023))  [![Project](https://img.shields.io/badge/Project-Page-blue.svg)]() 

## :bookmark: News!!!
- [x] 2024-*** **Arxiv Version has been released.**
- [ ] The code will be released soon.



## Abstract

Real-world image super-resolution (Real SR) aims to generate high-fidelity, detail-rich high-resolution (HR) images from low-resolution (LR) counterparts. Existing Real SR methods primarily focus on generating details from the LR RGB domain, often leading to a lack of richness or fidelity in fine details. In this paper, we pioneer the use of details hidden in RAW data to complement existing RGB-only methods, yielding superior outputs. We argue that key image processing steps in Image Signal Processing, such as denoising and demosaicing, inherently result in the loss of fine details in LR images, making LR RAW a valuable information source. To validate this, we present RealSR-RAW, a comprehensive dataset comprising over 10,000 pairs with LR and HR RGB images, along with corresponding LR RAW, captured across multiple smartphones under varying focal lengths and diverse scenes. Additionally, we propose a novel, general RAW adapter to efficiently integrate LR RAW data into existing CNNs, Transformers, and Diffusion-based Real SR models by suppressing the noise contained in LR RAW and aligning its distribution. Extensive experiments demonstrate that incorporating RAW data significantly enhances detail recovery and improves Real SR performance across ten evaluation metrics, including both fidelity and perception-oriented metrics. Our findings open a new direction for the Real SR task, with the dataset and code will be made available to support future research.

## Framework
![Framework-final](Framework-final.png)


## :sparkles: Getting Start

### Prepare environment


## Cite US
Please cite us if this work is helpful to you.



## Acknowledgments
The basic code is partially from the below repos.
- [BasicSR]([link](https://github.com/XPixelGroup/BasicSR))
