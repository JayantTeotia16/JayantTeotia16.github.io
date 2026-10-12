---
title: "OGP-Net: Optical Guidance Meets Pixel-Level Contrastive Distillation for Robust Multi-Modal and Missing Modality Segmentation"
collection: publications
permalink: /publication/csknet
paperurl: 'https://arxiv.org/abs/2312.02240'
date: 2025-02-25
venue: 'AAAI 2025'
citation: 'A. Sikdar, <b>J. Teotia</b>, S. Sundaram. <i>OGP-Net: Optical Guidance Meets Pixel-Level Contrastive Distillation for Robust Multi-Modal and Missing Modality Segmentation.</i> AAAI 2025, pp. 6922–6930.'
---

Improving the performance of semantic segmentation models using multispectral information is crucial, especially for environments with low-light and adverse conditions. Multi-modal fusion techniques pursue either the learning of cross-modality features to generate a fused image or engage in knowledge distillation but address multimodal and missing modality scenarios as distinct issues, which is not an optimal approach for multi-sensor models. To address this, a novel multi-modal fusion approach called CSK-Net is proposed, which uses a contrastive learning-based spectral knowledge distillation technique along with an automatic mixed feature exchange mechanism for semantic segmentation in optical (EO) and infrared (IR) images. The distillation scheme extracts detailed textures from the optical images and distills them into the optical branch of CSK-Net. The model encoder consists of shared convolution weights with separate batch norm (BN) layers for both modalities, to capture the multi-spectral information from different modalities of the same objects. A Novel Gated Spectral Unit (GSU) and mixed feature exchange strategy are proposed to increase the correlation of modality-shared information and decrease the modality-specific information during the distillation process. Comprehensive experiments show that CSK-Net surpasses state-of-the-art models in multi-modal tasks and for missing modalities when exclusively utilizing IR data for inference across three public benchmarking datasets. For missing modality scenarios, the performance increase is achieved without additional computational costs compared to the baseline segmentation models. 

A. Sikdar, <b>J. Teotia</b>, S. Sundaram. *OGP-Net: Optical Guidance Meets Pixel-Level Contrastive Distillation for Robust Multi-Modal and Missing Modality Segmentation.* In Proceedings of AAAI 2025, pp. 6922–6930.

The abstract above is from the earlier arXiv preprint (CSK-Net). [arXiv preprint](https://arxiv.org/abs/2312.02240)