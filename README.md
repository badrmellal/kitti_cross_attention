### Multimodal Contrastive Learning with Cross-Attention Fusion

RGB Camera + LiDAR (BEV)
<img width="1207" height="428" alt="Screenshot 2026-04-28 at 00 07 39" src="https://github.com/user-attachments/assets/4e7879bc-7ab6-4c22-8f85-a1b1977393e1" />

## Overview

This project implements a self-supervised multimodal representation learning framework that fuses RGB images and LiDAR Bird’s Eye View (BEV) using cross-attention inside the encoder.

The model learns joint representations by:

Allowing image tokens to attend to BEV tokens
Allowing BEV tokens to attend to image tokens
Training with a contrastive objective (SimCLR / NT-Xent loss)

No labels are required.
Dataset used : kitti-3d-object-detection-dataset
