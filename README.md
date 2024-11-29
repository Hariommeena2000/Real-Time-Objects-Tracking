# Real Time Person Tracking in disaster Situation

<div align="center">
  <p>
  <img src="assets/images/result_StrongSort (1) (1) (1).mp4" width="400"/>
  </p>
  <br>
  <div>
  <a href="https://github.com/mikel-brostrom/yolov8_tracking/actions/workflows/ci.yml"><img src="https://github.com/mikel-brostrom/yolov8_tracking/actions/workflows/ci.yml/badge.svg" alt="CI CPU testing"></a>
  <a href="https://pepy.tech/project/boxmot"><img src="https://static.pepy.tech/badge/boxmot"></a>
  <br>
  <a href="https://colab.research.google.com/drive/18nIqkBr68TkK8dHdarxTco6svHUJGggY?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>
<a href="https://doi.org/10.5281/zenodo.8132989"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.8132989.svg" alt="DOI"></a>
<a href="https://hub.docker.com/r/boxmot/boxmot"><img src="https://img.shields.io/docker/pulls/boxmot/boxmot?logo=docker" alt="Ultralytics Docker Pulls"></a>

  </div>
</div>

## Introduction

This repo contains a collections of pluggable state-of-the-art multi-object trackers for segmentation, object detection and pose estimation models. For the methods using appearance description, both heavy ([CLIPReID](https://arxiv.org/pdf/2211.13977.pdf)) and lightweight state-of-the-art ReID models ([LightMBN](https://arxiv.org/pdf/2101.10774.pdf), [OSNet](https://arxiv.org/pdf/1905.00953.pdf) and more) are available for automatic download. We provide examples on how to use this package together with popular object detection models such as: [YOLOv8, YOLOv9 and YOLOv10](https://github.com/ultralytics)


#### News

* Added YOLOv9 and YOLOv10 support
* 
Today's multi-object tracking options are heavily dependant on the computation capabilities of the underlaying hardware. BoxMOT provides a great variety of tracking methods that meet different hardware limitations, all the way from CPU only to larger GPUs. Morover, we provide scripts for ultra fast experimentation by saving detections and embeddings, which then be loaded into any tracking algorithm. Avoiding the overhead of repeatedly generating this data.

## Installation

Start with [**Python>=3.9**](https://www.python.org/) environment.

