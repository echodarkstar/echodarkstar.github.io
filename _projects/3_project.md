---
layout: page
title: FaceVer
description: Siamese Networks for face verification
img: /assets/img/facever.png
importance: 6
category: hackathon
---

This project was made for a 3 month long hackathon conducted by Mastek called Project Deep Blue. Our team won the 2nd prize in the competition, and we later deployed the solution.

<a href="https://arxiv.org/abs/1811.06194v1">Paper</a>

<a href="https://github.com/echodarkstar/Face-verification-siamese-network">Code</a>

#### Abstract:

Although modern face verification systems are accessible and accurate, they are not always robust to pose variance and occlusions. Moreover, accurate models require a large amount of data to train. We structure our experiments to operate on small amounts of data obtained from an NGO that funds opthalmic surgeries. We set up our face verification task as that of verifying pre-operation and post-operation images of a patient that undergoes opthalmic surgery, and as such the post-operation images have occlusions like an eye patch. In this paper, we present a system that performs the face verification task using one-shot learning. To this end, our paper uses deep convolutional networks and compares different model architectures and loss functions. Our best model achieves 85% test accuracy. During inference time, we also attemt to detect image forgeries in addition to performing face verification. To achieve this, we use Error Level Analysis. Finally, we propose an inference pipeline that demonstrates how these techniques can be used to implement an automated face verification and forgery detection system.