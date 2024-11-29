# Real Time Person Tracking in disaster Situation

<div align="center">
  <p>
  <img src="assets/images/result_StrongSort111-ezgif.com-video-to-gif-converter.gif" width="400"/>
  </p>
</div>

## Introduction

This repo contains a collections of pluggable state-of-the-art multi-object trackers for segmentation, object detection and pose estimation models. For the methods using appearance description, both heavy ([CLIPReID](https://arxiv.org/pdf/2211.13977.pdf)) and lightweight state-of-the-art ReID models ([LightMBN](https://arxiv.org/pdf/2101.10774.pdf), [OSNet](https://arxiv.org/pdf/1905.00953.pdf) and more) are available for automatic download. We provide examples on how to use this package together with popular object detection models such as: [YOLOv8, YOLOv9 and YOLOv10](https://github.com/ultralytics)


#### News

* Added YOLOv9 and YOLOv10 support
* 
Today's multi-object tracking options are heavily dependant on the computation capabilities of the underlaying hardware. BoxMOT provides a great variety of tracking methods that meet different hardware limitations, all the way from CPU only to larger GPUs. Morover, we provide scripts for ultra fast experimentation by saving detections and embeddings, which then be loaded into any tracking algorithm. Avoiding the overhead of repeatedly generating this data.

## Installation

Start with [**Python>=3.9**](https://www.python.org/) environment.

