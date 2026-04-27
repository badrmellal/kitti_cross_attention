### Multimodal Contrastive Learning with Cross-Attention Fusion

RGB Camera + LiDAR (BEV)

## Overview

This project implements a self-supervised multimodal representation learning framework that fuses RGB images and LiDAR Bird’s Eye View (BEV) using cross-attention inside the encoder.

The model learns joint representations by:

Allowing image tokens to attend to BEV tokens
Allowing BEV tokens to attend to image tokens
Training with a contrastive objective (SimCLR / NT-Xent loss)

No labels are required.
Dataset used : kitti-3d-object-detection-dataset
