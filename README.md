# Acoustic Drone Detection - Thesis Code

GENG4412/5512 Engineering Research Project, University of Western Australia.

This repository contains the Jupyter/Colab notebooks for training and evaluating three architectures for acoustic drone detection:

- CNN v3
- LWCNN (Lightweight CNN)
- CNN-Transformer

## Layout

- `notebooks/final/` - final benchmark and thesis-results notebooks
- `notebooks/training/` - model training notebooks
- `notebooks/evaluation/` - standalone evaluation notebooks
- `notebooks/visualisation/` - data augmentation visualisation

## Model weights

Trained model weights are not stored in this repository (they exceed GitHub's file size limits). They are held separately in the `Models and weights` folder on Google Drive.

## Reproducibility

All notebooks are designed to run in Google Colab with Drive mounted at `/content/drive`. Paths to datasets and weights are set inside each notebook.
