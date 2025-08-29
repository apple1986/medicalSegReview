# medicalSegReview
Is the medical image segmentation problem solved? A survey of current developments and future directions

This paper is available for download at https://arxiv.org/abs/2508.20139.

# Representative Methods: 2015–2024

<div style="overflow-x: auto;">

| Time  | Method| Title | Link |
|-------|------|----------|------|
| 2015  | FCN       | Fully Convolutional Networks for Semantic Segmentation | [Link](https://arxiv.org/abs/1411.4038) |
| 2015  | SegNet    | SegNet: A Deep Convolutional Encoder-Decoder Architecture for Image Segmentation | [Link](https://arxiv.org/abs/1511.00561) |
| 2015  | 2D U-Net  | U-Net: Convolutional Networks for Biomedical Image Segmentation | [Link](https://arxiv.org/abs/1505.04597) |
| 2016  | V-Net     | V-Net: Fully Convolutional Neural Networks for Volumetric Medical Image Segmentation | [Link](https://arxiv.org/abs/1606.04797) |
| 2016  | 3D U-Net  | 3D U-Net: Learning Dense Volumetric Segmentation from Sparse Annotation | [Link](https://arxiv.org/abs/1606.06650) |
| 2017  | LinkNet   | LinkNet: Exploiting Encoder Representations for Efficient Semantic Segmentation | [Link](https://arxiv.org/abs/1707.03718) |
| 2017  | DeepLab   | DeepLab: Semantic Image Segmentation with Deep Convolutional Nets, Atrous Convolution, and Fully Connected CRFs | [Link](https://arxiv.org/abs/1606.00915) |
| 2018  | UNet++    | UNet++: A Nested U-Net Architecture for Medical Image Segmentation | [Link](https://arxiv.org/abs/1807.10165) |
| 2018  | Attention U-Net | Attention U-Net: Learning Where to Look for the Pancreas | [Link](https://arxiv.org/abs/1804.03999) |
| 2018  | nnU-Net   | nnU-Net: Self-adapting Framework for U-Net-Based Medical Image Segmentation | [Link](https://arxiv.org/abs/1809.10486) |
| 2018  | UperNet   | Unified Perceptual Parsing for Scene Understanding | [Link](https://arxiv.org/abs/1807.10221) |
| 2019  | FD-UNet   | FD-UNet: Fourier Domain UNet for Fast MR Image Reconstruction | [Link](https://arxiv.org/abs/1910.02891) |
| 2019  | DUNet     | DUNet: A Deformable Network for Retinal Vessel Segmentation | [Link](https://arxiv.org/abs/1904.02161) |
| 2019  | SegResNet | SegResNet: A Residual Encoder-Decoder Architecture for Image Segmentation | [Link](https://arxiv.org/abs/1904.00592) |
| 2019  | CCNet     | CCNet: Criss-Cross Attention for Semantic Segmentation | [Link](https://arxiv.org/abs/1811.11721) |
| 2020  | UNet 3+   | UNet 3+: A Full-Scale Connected UNet for Medical Image Segmentation | [Link](https://arxiv.org/abs/2004.08790) |
| 2020  | MA-Net    | MA-Net: A Multi-scale Attention Network for Liver and Tumor Segmentation | [Link](https://arxiv.org/abs/2007.09125) |
| 2020  | RA-UNet   | RA-UNet: A Hybrid Residual Attention-Aware U-Net for Liver Tumor Segmentation | [Link](https://arxiv.org/abs/1811.01328) |
| 2020  | COPLE-Net | COPLE-Net: Convolutional Pose-guided Label Enhancement for Medical Segmentation | [Link](https://arxiv.org/abs/2006.15223) |
| 2021  | Swin UNETR | Swin UNETR: Swin Transformers for Semantic Segmentation of Brain Tumors in MRI | [Link](https://arxiv.org/abs/2201.01266) |
| 2021  | TransUNet | TransUNet: Transformers Make Strong Encoders for Medical Image Segmentation | [Link](https://arxiv.org/abs/2102.04306) |
| 2021  | SegFormer | SegFormer: Simple and Efficient Design for Semantic Segmentation with Transformers | [Link](https://arxiv.org/abs/2105.15203) |
| 2021  | Swin-Unet | Swin-Unet: Unet-like Pure Transformer for Medical Image Segmentation | [Link](https://arxiv.org/abs/2105.05537) |
| 2022  | LeViT-UNet | LeViT-UNet: Make Faster Encoders with Transformer for Medical Image Segmentation | [Link](https://arxiv.org/abs/2203.04245) |
| 2022  | MISSFormer | MISSFormer: Medical Image Segmentation via Self-Supervised Transformer | [Link](https://arxiv.org/abs/2109.04540) |
| 2022  | SegNeXt   | SegNeXt: Rethinking Convolutional Attention Design for Semantic Segmentation | [Link](https://arxiv.org/abs/2209.08575) |
| 2022  | UNeXt     | UNeXt: MLP-based Medical Image Segmentation | [Link](https://arxiv.org/abs/2203.04967) |
| 2022  | UniMatch  | Semi-Supervised Medical Image Segmentation with Cross Pseudo Supervision | [Link](https://arxiv.org/abs/2206.08549) |
| 2023  | SAM       | Segment Anything | [Link](https://arxiv.org/abs/2304.02643) |
| 2023  | MobileSAM | MobileSAM: Lightweight Segment Anything Model | [Link](https://arxiv.org/abs/2306.14289) |
| 2023  | MedSAM    | MedSAM: Segment Anything in Medical Images | [Link](https://arxiv.org/abs/2304.12620) |
| 2024  | SAM2      | Segment Anything Model 2 | [Link](https://arxiv.org/abs/2408.00714) |
| 2024  | VM-UNet   | VM-UNet: Vision Mamba for Medical Image Segmentation | [Link](https://arxiv.org/abs/2401.10166) |
| 2024  | Mamba-UNet | Mamba-UNet: State Space Model U-Net for Medical Image Segmentation | [Link](https://arxiv.org/abs/2402.04790) |

</div>


  <br>
  <br>
<br>

# Table 1. Representative fully supervised learning–based methods for medical image segmentation

| Method        | Year | Key Contribution                                                                                       | Modality                              | Source Code |
|---------------|------|-------------------------------------------------------------------------------------------------------|---------------------------------------|-------------|
| U-Net    | 2015 | Encoder–decoder with skip connections for precise localization; small data efficiency                 | Biomedical microscopy, general medical imaging | [Link](https://github.com/milesial/Pytorch-UNet) |
| V-Net    | 2016 | 3D fully convolutional network for volumetric segmentation with Dice loss                             | MRI volumetric segmentation           | [Link](https://github.com/faustomilletari/VNet) |
| nnU-Net  | 2021 | Self-configuring framework that adapts preprocessing, architecture, training to dataset               | Multi-modal segmentation (CT, MRI, PET) | [Link](https://github.com/MIC-DKFZ/nnUNet) |
| Attention U-Net | 2018 | Attention gates for focusing on relevant spatial regions                                         | CT, MRI lesion segmentation           | [Link](https://github.com/ozan-oktay/Attention-Gated-Networks) |
| UNet++  | 2018 | Nested and dense skip connections to reduce semantic gap between encoder and decoder                  | Multi-organ segmentation              | [Link](https://github.com/MrGiovanni/UNetPlusPlus) |
| TransUNet | 2021 | Combines Transformer encoder with CNN decoder for global context                                      | Multi-modal MRI/CT segmentation       | [Link](https://github.com/Beckschen/TransUNet) |
| LeViT-UNet | 2021 | Lightweight hybrid CNN–Transformer architecture (LeViT backbone) integrated into a U-Net framework for fast and accurate medical image segmentation | CT, MRI | [Link](https://github.com/apple1986/LeViT-UNet) |
| Swin-UNet | 2022 | Hierarchical Swin Transformer for medical image segmentation                                         | CT, MRI                               | [Link](https://github.com/HuCaoFighting/Swin-Unet) |
| SwinUNETR     | 2022 | Combines a Swin Transformer encoder with a UNETR-style decoder for high-performance 3D CT/MRI segmentation | 3D CT, 3D MRI                        | [Link](https://monai.io/research/swin-unetr) |
| SAM      | 2023 | Promptable image segmentation foundation model trained on 1B masks; adaptable to medical imaging via fine-tuning | Natural & medical images | [Link](https://github.com/facebookresearch/segment-anything) |
| SAM2     | 2024 | Next-generation SAM with improved memory mechanisms for efficient multi-object and video segmentation; better performance in domain adaptation | Natural & medical images, video sequences | [Link](https://github.com/facebookresearch/segment-anything-2) |


# Table 2. Representative semi-supervised learning methods for medical image segmentation

| Method       | Year | Key Contribution                                                                                       | Application Domain                   | Source Code |
|--------------|------|-------------------------------------------------------------------------------------------------------|--------------------------------------|-------------|
| UA-MT  | 2019 | Combines mean teacher consistency with uncertainty weighting                                          | 3D medical image segmentation        | [Link](https://github.com/yulequan/UA-MT) |
| FixMatch | 2020 | Combines consistency regularization with pseudo-labeling using strong/weak augmentations             | Multi-domain segmentation            | [Link](https://github.com/kekmodel/FixMatch-pytorch) |
| CPS    | 2021 | Two-network pseudo label exchange to improve consistency                                               | General image segmentation; adapted to medical | [Link](https://github.com/charlesCXK/TorchSemiSeg) |
| DTC    | 2021 | Enforces consistency between segmentation and boundary prediction                                     | Multi-organ CT segmentation          | [Link](https://github.com/HiLab-git/DTC) |
| MC-Net | 2021 | Multi-branch co-training with temporal ensembling                                                     | Cardiac MRI segmentation             | [Link](https://github.com/ycwu1997/MC-Net) |
| URPC   | 2021 | Uncertainty Rectified Pyramid Consistency for semi-supervised learning                                | CT organ segmentation                | [Link](https://github.com/HiLab-git/URPC) |
| UniMatch | 2022 | Unified semi-supervised segmentation framework that balances strong and weak consistency constraints with adaptive thresholding | General image segmentation; adapted to medical | [Link](https://github.com/LiheYoung/UniMatch) |
| UniMatch v2 | 2023 | Improves UniMatch with multi-view consistency, dynamic confidence thresholds, and stronger augmentation strategies | General image segmentation; adapted to medical | [Link](https://github.com/LiheYoung/UniMatch) |
| SAMatch | 2024 | Leverages the Segment Anything Model (SAM) to generate high quality pseudo-labels for U-Net          | Multi-organ and lesion segmentation in CT/MRI/US | [Link](https://github.com/apple1986/SAMatch) |


# Table 3. Representative public datasets for lesion segmentation on medical image

| Dataset       | Year | Scans (Train/Test) | Lesion/Target                | Region     | Modality | Description |
|---------------|------|--------------------|------------------------------|------------|----------|-------------|
| BraTS   | 2012 | 50/15              | Brain tumors (gliomas)       | Brain      | MRI      | Multi-parametric MRI (T1, T1Gd, T2, FLAIR) with expert annotations for tumor subregions, including enhancing tumor, tumor core, and whole tumor. Released annually with varying train/test splits: BraTS 2018 (210/75), BraTS 2019 (256/76), BraTS 2020 (369/125), BraTS 2021 (~2,000 cases), and BraTS 2023 (~2,400 cases) |
| ISLES   | 2015 | 28/36 (SISS); 30/20 (SPES) | Ischemic stroke lesions      | Brain      | MRI      | Multi-sequence MRI (DWI, FLAIR, T2) for acute and subacute stroke lesion segmentation, comprising two subsets: Sub-Acute Stroke Lesion Segmentation (SISS) and Stroke Perfusion Estimation (SPES); later expanded to ISLES16/17 and ISLES24 |
| ATLAS   | 2018 | 955/245            | Stroke lesions               | Brain      | MRI      | Anatomical Tracings of Lesions After Stroke. T1-weighted MRI with manually delineated lesions. |
| SegTHOR | 2020 | 40/20              | Thoracic tumors (esophageal) | Thorax     | CT       | Segmentation of esophagus, heart, trachea, and tumor from thoracic CT scans. |
| HECKTOR | 2020 | 201/53             | Head & neck squamous cell carcinoma | Head & Neck | PET/CT   | Multi-institutional dataset for tumor segmentation in head and neck cancer; expanded to 224/101 cases in 2021 and 524/359 cases in 2022. |
| LiTS    | 2017 | 131/70             | Liver tumors                 | Abdomen    | CT       | Contrast-enhanced abdominal CT scans for liver and lesion segmentation. |
| KiTS19  | 2019 | 210/90             | Kidney tumors                | Abdomen    | CT       | Kidney and kidney tumor segmentation from contrast-enhanced abdominal CT scans; expanded in KiTS21 to 300/100 cases in 2021. |
| MSD – Hepatic Vessel [272, 298] | 2019 | 303/140 | Liver tumors & vessels | Abdomen    | CT       | From Medical Segmentation Decathlon (Task 08). Contrast-enhanced abdominal CT with hepatic vessel and tumor labels. |
| MSD – Pancreas [272, 298] | 2019 | 282/138 | Pancreatic tumors            | Abdomen    | CT       | From Medical Segmentation Decathlon (Task 07). Abdominal CT for pancreas and pancreatic tumor segmentation. |
| MSD – Lung [272, 298] | 2019 | 63/33      | Lung tumors                  | Abdomen    | CT       | From Medical Segmentation Decathlon (Task 06). Thoracic CT for lung cancer segmentation. |
| MSD – Colon [272, 298] | 2019 | 126/64    | Colon tumors                 | Abdomen    | MRI      | From Medical Segmentation Decathlon (Task 10). Pelvic MRI for colorectal cancer segmentation. |
| PROMISE12 | 2012 | 50/50           | Prostate lesions             | Pelvis     | MRI      | T2-weighted prostate MRI for prostate gland segmentation. |
