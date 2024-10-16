# DPD-AITAFC
Here is a detailed description of the GitHub repository, written in a format suitable for a GitHub page, for the paper titled *"Sparse Emotion Dictionary and CWT Spectrogram Fusion with Multi-head Self-Attention for Depression Recognition in Parkinson's Disease Patients"*. This repository will include the dataset and code after the paper's official release.

---

# Sparse Emotion Dictionary and CWT Spectrogram Fusion with Multi-head Self-Attention for Depression Recognition in Parkinson's Disease Patients

Welcome to the official repository for the paper **"Sparse Emotion Dictionary and CWT Spectrogram Fusion with Multi-head Self-Attention for Depression Recognition in Parkinson's Disease Patients"**, published in IEEE Transactions on Affective Computing.

## Overview

This project addresses the challenge of depression recognition in Parkinson's Disease (PD) patients by fusing **textual** and **spectral features** from interview audio. The goal is to improve the precision of depression detection using a **Sparse Emotion Dictionary** and **Continuous Wavelet Transform (CWT) Spectrogram** combined with a **Multi-head Self-Attention (MSA)** mechanism.

### Key Contributions:
1. **Sparse Emotion Dictionary**: Extracts textual features representing emotional expressions from interview audio, translating these into images for emotional analysis.
2. **CWT Spectrogram**: Transforms audio data into spectral images using Continuous Wavelet Transform (CWT) to capture frequency and temporal characteristics.
3. **High and Low Frequency Feature Fusion**: Employs a novel High-Low frequency feature fusion within a Vision Transformer (ViT), enabling the combination of both high-resolution and low-resolution emotional cues.
4. **Depression Dataset**: A specialized dataset for PD and depression, incorporating both emotional and speech data from PD patients.

## Contents

- **Dataset**: Includes audio data and corresponding emotional features extracted from interviews of PD patients. The dataset will be publicly available upon publication.
- **Code**: Contains scripts for processing audio data, generating the Sparse Emotion Dictionary, creating CWT spectrograms, and implementing the depression recognition model using multi-head self-attention.

## Repository Structure

- `/data`: Placeholder for the dataset (available after publication).
- `/src`: Code for feature extraction, image fusion, and model implementation.
  - `feature_extraction.py`: Scripts for generating the Sparse Emotion Dictionary and CWT spectrogram.
  - `model.py`: Implementation of the High-Low frequency feature fusion network using Vision Transformer.
  - `train.py`: Training and evaluation scripts for the depression recognition model.
- `/notebooks`: Jupyter notebooks for data exploration and visualization.
- `/results`: Example outputs from the model including classification metrics and visualizations.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/depression-recognition-PD.git
   cd depression-recognition-PD
   ```
2. Download the dataset (available after publication).
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the preprocessing scripts to generate dictionary images and spectrograms:
   ```bash
   python src/feature_extraction.py
   ```
5. Train the model:
   ```bash
   python src/train.py
   ```

## Citation

If you use the dataset or code, please cite the paper as follows:
```
@article{li2024sparse,
  title={Sparse Emotion Dictionary and CWT Spectrogram Fusion with Multi-head Self-Attention for Depression Recognition in Parkinson's Disease Patients},
  author={Li, Jian and Liu, Yinghao and Zhang, Huawei and Zhao, Yuliang and others},
  journal={IEEE Transactions on Affective Computing},
  year={2024}
}
```



The dataset and code will be made publicly available after the official publication of the paper. Stay tuned for updates!
