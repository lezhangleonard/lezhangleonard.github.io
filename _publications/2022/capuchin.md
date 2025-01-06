---
title:          "Demo Abstract: Capuchin: A Neural Network Model Generator for 16-bit Microcontrollers"
date:           2022-05-20 00:01:00 -0500
selected:       true
pub:            "International Conference on Information Processing in Sensor Networks (IPSN)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_date:       "2022"

abstract: >-
  Resource-optimized deep neural networks (DNNs) nowadays run on microcontrollers to perform a wide variety of audio, image and sensor data classification tasks. Despite comprehensive support for deep learning tools for 32-bit microcontrollers, performing deep learning inferences on 16-bit microcontrollers still remains a chal-lenge. Although there are some tools for implementing neural net-works on 16-bit systems, generally, there is a large gap in efficiency between the development tools for 16-bit microcontrollers and 32-bit (or higher) systems. There is also a steep learning curve that discourages beginners inexperienced with microcontrollers and programming in C to develop efficient and effective deep learning models for 16-bit microcontrollers. To fill this gap, we have created a neural network model generator that (1) automatically transfers parameters of a pre-trained DNN or CNN model from commonly used frameworks to a 16-bit microcontroller, and (2) automatically implements the model on the microcontroller to perform on-device inference. The optimization of data transfer saves time and mini-mizes chances of error, and the automatic implementation reduces the complexity to implement DNNs and CNNs on ultra-low-power microcontrollers.

cover:          /assets/images/covers/capuchin.png
authors:
  - Le Zhang
  - Yubo Luo
  - Shahriar Nirjon
links:
  Paper: https://yuboluo.github.io/publication/07_capuchin/07_Capuchin.pdf
  Code: https://github.com/lezhangleonard/Capuchin
---

