Here is the project page of PipID.
# Pupil Diameter Data Processing & Classification


## Introduction
This project focuses on processing eye-tracking data, including data preprocessing, feature extraction, and classification model training.

## File Structure
- **`main.ipynb`**:  
  - Jupyter Notebook for data loading, preprocessing, and feature extraction.  

- **`constant.py`**:  
  - Stores constant parameters used across the project (e.g., sampling numbers, user numbers).  

- **`process_txt.py`**:  
  - Functions to read raw eye-tracking data from text files.  

- **`denoise.py`**:  
  - Denoising, resampling, and filtering functions for raw data.  

- **`fft.py`**:  
  - Fourier Transform (FFT) and frequency-domain analysis functions.  

- **`stimuli_design.py`**:  
  - Custom wavelength selection using the Kolmogorov-Smirnov (KS) test for stimuli design.  

- **`feature_extractor.py`**:  
  - Extracts statistical and time-domain features.  
  - Calls short-time FFT and frequency-domain functions from `short_fft.py`.  
  - Includes random sample combination, feature expanding, and final feature generation for training.  

- **`short_fft.py`**:  
  - Implements short-time Fourier Transform (STFT) and frequency-domain feature extraction.  

- **`classify.ipynb`**:  
  - Jupyter Notebook for training sample extraction, classification model training, and evaluation experiments.  

- **`classify.py`**:  
  - Functions for model training, validation, and experimentation.  

