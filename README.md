# Fourier Analysis for Materials Microstructure Characterization

This repository contains three demonstrations of Fast Fourier Transform (FFT) applications in materials science microscopy.

## Demonstrations

### Demo 1: FFT-Based Denoising
Removes noise from microscopy images by filtering out low-magnitude frequency components while preserving important structural features.

### Demo 2: Bandpass Filtering for Feature Separation
Separates microstructural features by size using frequency domain filtering:
- Large features (grain structure)
- Medium features
- Fine features (precipitates)

### Demo 3: Anisotropy Detection in Cold-Rolled Steel
Quantifies directional preferences in microstructures by analyzing power distribution in frequency space. Successfully differentiates between steel samples with 30% and 90% cold rolling reduction.

## Requirements
- Python 3.x
- NumPy
- Matplotlib
- imageio
- scikit-image

## Usage
Run the Jupyter notebook `Demo1_commented.ipynb` to execute all three demonstrations with detailed explanations of each step.

## Image Attribution
Microstructure images used in these demonstrations are from:

Vander Voort, G. F. (Ed.). (2004). *Metallography and Microstructures* (Vol. 9). ASM International. https://doi.org/10.31399/asm.hb.v09.9781627081771

## Applications
These techniques are applicable to:
- Materials characterization
- Quality control in manufacturing
- Microstructure analysis
- Grain size measurement
- Defect detection
