---
layout: post
title:  "Online Camera-LiDAR Calibration with Sensor Semantic Information"
date:   2020-05-18
excerpt: "Yufeng Zhu, Chenghui Li, Yubo Zhang
International Conference on Robotics and Automation 2020, Paris"
project: true
tag:
- blog
- computer vision
comments: false
---

## About this project
I conducted this project with [Yufeng Zhu](https://mike323zyf.github.io/) and [Yubo Zhang](https://www.linkedin.com/in/yubo-zhang-0369659/)  when I was an intern at `Pony.AI` in 2019 summer.

## Intro

### Keywords
Sensor fusion, sensor calibration, semantic segmentation, LiDAR, online calibration. 

### Major idea
We investigate the extrinsic calibration of an RGB camera and a light detection
and ranging (LiDAR) sensor, which are two of the most widely used sensors in autonomous vehicles for perceiving the outdoor environment.

Specifically, we introduce an online calibration technique that automatically computes the optimal rigid motion transformation between the aforementioned two sensors and maximizes their mutual information of perceived data, without the need of tuning environment settings. By formulating the calibration as an optimization problem with a calibration
quality metric based on semantic features, we successfully align pairs of temporally synchronized camera and LiDAR frames in real time.

## Open sourced ?
Not yet.

