***Fed-MUnet: Multi-modal Federated U-Net for Brain Tumor Segmentation at DKU***
📆03/2024-08/2024
👨‍🏫Research Assistant to Professor Bing Luo：Assistant Professor of Data and Computational Science	📍Kunshan, China

[Zhou, Ruojun, Lisha Qu, Lei Zhang, Ziming Li, Hongwei Yu, and Bing Luo. "Fed-MUnet: Multi-modal Federated Unet for Brain Tumor Segmentation." arXiv preprint arXiv:2409.01020 (2024).](./poster.pdf)



Privacy-preserving federated learning (FL) for multi-hospital MRI segmentation. A lightweight U-Net with a Cross-Modality Module (CMM) fuses T1/T1c/T2/FLAIR features; server-side clipped aggregation with calibrated noise stabilizes non-IID clients. On BraTS-style benchmarks, Fed-MUnet approaches centralized performance while keeping data on-prem.

Core ideas
	•	CMM fusion: transformer-style cross-attention aligns modalities to sharpen ET/TC/WT boundaries.
	•	Efficient backbone: depth-wise U-Net blocks balance accuracy and compute.
	•	Robust FL: flat-clipping + noise reduces client drift under heterogeneous data.

	•	Training paradigm (Fig. 1):
	•	Decentralized Training Paradigm for Brain Tumor Segmentation.
![Federated training rounds](images/fedmunet_paradigm.png "Client–server FL for MRI segmentation")
	•	Model architecture with CMM (Fig. 2):
    Fig. 2: The framework of our segmentation backbone M-Unet. The right part is the structure of CMM. The overall framework follows the encoder-decoder architecture of Unet and a Transformer-like module CMM is used for multi-modal feature integration. For concatenation, we deploy a convolution operation to align the dimension of upsampling feature matrix
![Fed-MUnet + CMM](images/munet_cmm_arch.png "U-Net encoder–decoder with cross-modal fusion")

	•	Qualitative results vs. ground truth (Fig. 3):
    Examples of Segmentation Results and Ground Truth. The area marked by the red circle is the difference between the true label and the inference result of the model with σ= 10^−5
![BraTS samples: prediction vs label](images/brats_samples.png "ET/TC/WT overlays")


