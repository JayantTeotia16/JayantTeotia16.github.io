---
title: "Object detection using rotation equivariant networks for gravity free images @RBCCPS"
excerpt: "<br/><img src='/images/P0006.png'>"
collection: portfolio

---

* The images taken from birds-eye view are gravity free in the essence that objects present in those images are randomly oriented(rotated).
* Traditional model's performance decreases in these scenarios as a large amount of data and augmentations are needed to take into account the arbitrary rotation of objects.
* For these scenarios, the detection is better performed by models which are rotation equivariant and invariant.
* I was responsible for training and inferencing ReDet(Rotation Equivariant Detector) and ORCNN(Oriented RCNN) on our custom drone dataset which consists of images in birds eye view as well as the slant angle view.
* ReDet and ORCNN performs with 80.10% and 80.87% mAP on DOTA dataset, which is a public dataset for detection task.
* These models were trained on NVIDIA A6000 and deployed on NVIDIA DGX.

