# Spectral Physical Unclonable Functions: Downscaling Randomness with Multi-Resonant Hybrid Particles

This repository contains the implementation for our paper "Spectral Physical Unclonable Functions: Downscaling Randomness with Multi-Resonant Hybrid Particles".

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

2. Run the Jupyter notebook `spectral-pufs.ipynb` to:
   - Preprocess the PL spectra
   - Train the authentication model
   - Evaluate the PUF performance

## Citation

If you use this code in your research, please cite our paper:

```@article{sandomirskii2025spectral,
	title	=	{Spectral physical unclonable functions: downscaling randomness with multi-resonant hybrid particles},
	author	=	{Sandomirskii, Martin and Petrova, Elena and Kustov, Pavel and Chizhov, Lev and Larin, Artem and Bruy{\ifmmode\grave{e}\else\`{e}\fi}re, St{\ifmmode\acute{e}\else\'{e}\fi}phanie and Yaroshenko, Vitaly and Ageev, Eduard and Belov, Pavel and Zuev, Dmitry},
	year	=	{2025}
}
```
