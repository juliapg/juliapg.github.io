---
layout: page
title: Deep Learning for Flow Velocity Estimation
description: PhD project
img: assets/img/doppler.jpg
importance: 1
category: work
---

Ultrasound imaging is the preferred modality for monitoring cardiac tissue and intracardiac blood flow due to its low cost, portability, and real-time capacity. In particular, it provides valuable markers for the evaluation of cardiac function. However, in some cases, these markers can lead to ambiguous diagnoses, motivating the exploration of new indicators. Recent studies have suggested considering other markers, such as intracardiac flow patterns. Color Doppler is an ultrasound technique that allows 2D visualization of intracardiac blood flow. Processing of color Doppler acquisitions involves clutter filtering of the signals to recover blood information, followed by Doppler velocity estimation. However, its low frame rate does not allow to monitor blood flow thoroughly
along the cardiac cycle, relegating it to a qualitative tool in clinical settings. One strategy to increase the frame rate of color Doppler is to reduce the number of temporal acquisitions used to reconstruct each frame. However, traditional processing methods for clutter filtering and Doppler velocity estimation are sensitive to reductions in the number of temporal acquisitions. In recent years, deep learning has found numerous applications in ultrasound imaging. In particular, convolutional neural networks have proven powerful at processing ultrasound signals and images for a wide variety of tasks. In this thesis, we investigated the performance of a fully deep learning-based color Doppler pipeline for processing acquisitions with a reduced number of temporal frames.
We hypothesized that the power of convolutional neural networks to leverage spatial information could compensate for the reduction in temporal points.