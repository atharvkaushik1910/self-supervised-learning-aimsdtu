# Self-Supervised Learning - AIMS-DTU Research Intern Round 2

This project implements and compares two self-supervised learning techniques for visual representation learning:

- **SimCLR** (Contrastive Learning)
- **MAE (Masked Autoencoder)** (Masked Image Modelling)

## Folder Structure

\begin{verbatim}
submission/
├── ssl_dataset/
│   ├── train.X1/
│   ├── train.X2/
│   ├── train.X3/
│   ├── train.X4/
│   ├── val.X/
│   └── Labels.json
├── SimCLR_TF_Pretraining.ipynb
├── SimCLR_Linear_Probing.ipynb
├── MAE_TF_Pretraining.ipynb
├── MAE_TF_Linear_Probing.ipynb
├── simclr_encoder.h5
├── mae_encoder_tf.h5
├── report.pdf
└── README.md
\end{verbatim}


## Setup Instructions

1. Make sure `ssl_dataset` is placed in the same directory as the notebooks.
2. Install dependencies (if needed):
   ```bash
   pip install tensorflow numpy matplotlib scikit-learn
