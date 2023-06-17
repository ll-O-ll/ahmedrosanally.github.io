---
date: '3'
title: 'Instrument Classifier Neural Network'
cover: './architecture-base.png'
github: 'https://github.com/ll-O-ll/instrClassifier'

tech:
  - PyTorch
  - FFmpeg
  - Google Collab
---


The project was split into two stages. Stage 1 builds a single instrument classifier model to predict one instrument playing in a single-instrument audio file. Stage 2 uses transfer learning from Stage 1's 1D CNN model architecture to predict which two instruments are playing in a music sample. The [IRMAS dataset](https://www.upf.edu/web/mtg/irmas) was used to train the model. Additionally, the entirety of the project was implemented using the [PyTorch library](https://github.com/pytorch/pytorch) and accelerated using GPUs on Google Collab.