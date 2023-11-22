---
title: "Underwater Object detection and improvement of inference time by a factor of 10 using model pruning and Knowledge Distillation @Artpark"
excerpt: "<br/><img src='/images/UW.png'>"
collection: portfolio

---

Briefly, I was involved in the project of Underwater object detection. This was different from from other detection projects in the way that instead of RGB images, this project incorporated Radar(Synthetic Aperture Radar) images. A lot of preprocessing techniques were tested to reduce the noise(additive as well as multiplicative or speckle noise). Also GAN's and autoencoders were employed to generate synthetic images owing to the dearth of samples. These were useful for attaining better classification accuracy.

After the preprocessing of the images, YOLO v3, Faster RCNN and SSD were trained on the same dataset for detection using Tensorflow. The inference time of YOLO v3 was 0.2 seconds on Nvidia A6000. To increase this performance, model pruning was performed with a threshold of 0.2 and knowledge distillation was done from the teacher model to the pruned model which gave the inference time of 0.02 seconds without significant accuracy degradation.