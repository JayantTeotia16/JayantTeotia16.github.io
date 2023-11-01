---
title: "Research Assistant @ Robert bosch Centre for Cyber Physical Systems, IISC Bangalore"
excerpt: "Creating DNNs for multimaodal image fusion and segmentation.<br/>"
collection: portfolio
---


## SK-Net: Spectral-based Knowledge Distillation in Low-Light Thermal Imagery for robotic perception

* A lot of research has been ongoing in multimodality image fusion(EO-IR-Depth) to mitigate the drawbacks of using only EO(electro-optical) images in segmentation or detection. The missing modality applications of these fusion models is still very less. If one of the images is corrupted due to any reason, these models perform poorly.
* I have developed a novel network architecture, SK-Net, to address this problem. The training for SK-Net is performed in two steps which require EO and their corresponding IR images. While inferencing only IR images are required.
* During training step one, the Deeplab-v3 model is trained on RGB images. In the training step two, The trained model is used for knowledge distillation into a new model which outputs a segmentation map corresponding to IR, EO and fused features. The fusion is performed using a gated spectral unit. This model also makes the use of contrastive learning for increasing the prediction accuracy.
* Our model outperforms the baseline model by 2.97% and 2.71% on MSRS and MVSS datasets respectively.


## Detection on Gravity-free Images

* The images taken from birds-eye view are gravity free in the essence that objects present in those images are randomly oriented(rotated).
* Traditional model's performance decreases in these scenarios as a large amount of data and augmentation are needed to take into account the arbitrary rotation.
* For these scenarios, the detection method is performed by models which are rotation equivariant and invariant.
* I was responsible for training and inferencing ReDet(Rotation Equivariant Detector) and ORCNN(Oriented RCNN) on our custom drone dataset which consists of images in birds eye view as well as slant angle view.