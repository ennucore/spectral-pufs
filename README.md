# Spectral Physical Unclonable Functions: Downscaling Randomness with Multi-Resonant Hybrid Particles

This repository contains the implementation for our paper "Spectral Physical Unclonable Functions: Downscaling Randomness with Multi-Resonant Hybrid Particles". The work presents a novel approach to optical physical unclonable functions (PUFs) based on random nanoscale variations within multiresonant gold-silicon particles.

## Overview

Traditional optical PUFs rely on microscopic spatial features, which are increasingly vulnerable to microscale manipulation techniques. Our approach overcomes these limitations by leveraging:

- Random nanoscale variations in multiresonant gold-silicon particles
- Unique spectral features in particles' photoluminescence (PL)
- Strong optical resonances for robust authentication

The implementation provides a multi-functional platform for:
- Robust authentication of goods
- Verification of individuals
- All-optical one-time password tokens

## Implementation Details

The code in `Unclonix.ipynb` implements the preprocessing and analysis pipeline for photoluminescence (PL) spectra. Key features include:

- Data preprocessing and filtering
- Spectrum analysis and feature extraction
- Training and validation data preparation
- Model implementation for PUF authentication

## Requirements

The implementation requires:
- Python 3.x
- PyTorch
- NumPy
- SciPy
- scikit-learn

## Usage

1. Download the required data:
```bash
wget ennucore.com/f/spectra.npz
```

2. Run the Jupyter notebook `Unclonix.ipynb` to:
   - Preprocess the PL spectra
   - Train the authentication model
   - Evaluate the PUF performance

## Data Structure

The implementation works with two types of spectra:
- 620nm spectra
- 730nm spectra

Each spectrum contains 1024 data points, and the dataset includes:
- Training data
- Validation data
- Test data

## Citation

If you use this code in your research, please cite our paper.
