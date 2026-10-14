# MRI Denoising & Enhancement Autoencoder Project

This repository contains the lightweight depthwise separable and heavy-capacity structural autoencoder models trained on the IXI brain MRI dataset with simulated low-field scanner noise conditions.

## Models Included
- `best_mri_robust_denoiser.keras`: High fidelity structural U-Net trained with SSIM + L1 loss.
- `lightweight_mri_denoiser.keras`: Compact autoencoder optimized for real-time mobile and embedded systems.
