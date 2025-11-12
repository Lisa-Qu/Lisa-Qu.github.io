---
title: "Fed-MUnet: Multi-modal Federated Unet for Brain Tumor Segmentation" 
authors:
- Ruojun Zhou 
- Lisha Qu
- Lei Zhang 
- Ziming Li
- Hongwei Yu 
- Bing Luo 
date: "2024-11-18T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-02-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]


# Publication name and optional abbreviated publication name.
publication: "2024 IEEE International Conference on E-health Networking, Application & Services (HealthCom)"
publication_short: "IEEE HealthCom 2024"

abstract: "Deep learning-based techniques have been widely utilized for brain tumor segmentation using both single and multi-modal Magnetic Resonance Imaging (MRI) images. Most current studies focus on centralized training due to the intrinsic challenge of data sharing across clinics. To mitigate privacy concerns, researchers have introduced Federated Learning (FL) methods to brain tumor segmentation tasks. However, currently such methods are focusing on single modal MRI, with limited study on multi-modal MRI. The challenges include complex structure, large-scale parameters, and overfitting issues of the FL based methods using multi-modal MRI. To address the above challenges, we propose a novel multi-modal FL framework for brain tumor segmentation (Fed-MUnet) that is suitable for FL training. We evaluate our approach with the BraTS2022 datasets, which are publicly available. The experimental results demonstrate that our framework achieves FL nature of distributed learning and privacy preserving. For the enhancing tumor, tumor core and whoe tumor, the mean of five major metrics were 87.5%, 90.6% and 92.2%, respectively, which were higher than SOTA methods while preserving privacy. In terms of parameters count, quantity of floating-point operations (FLOPs) and inference, Fed-MUnet is Pareto optimal compared with the state-of-the-art segmentation backbone while achieves higher performance and tackled privacy issue. "

# Summary. An optional shortened abstract.
summary: "We propose Fed-MUnet, a novel multi-modal Federated Learning (FL) framework for brain tumor segmentation. Our approach addresses the privacy challenges of data sharing and the technical challenges of multi-modal MRI in FL, such as complex structures and overfitting.Evaluated on the BraTS2022 dataset, Fed-MUnet achieves state-of-the-art performance (e.g., 92.2% mean metric for whole tumor) while preserving privacy and remaining computationally efficient."

tags:
- Federated Learning 
- Brain tumor segmentation 
- Multi-modality 
- BraTS2022 dataset

featured: true

hugoblox:
  ids: {}

links:
- type: publisher
  label: IEEE Xplore
  url: "https://ieeexplore.ieee.org/document/10880824"
- type: code
  url: "https://github.com/Arnold-Jun/Fed-MUnet" 
- type: dataset
  label: BraTS2022 Dataset
  url: "https://www.med.upenn.edu/cbica/brats2022/" 
---