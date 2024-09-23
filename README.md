# Audio Feature Engineering Assignment

## Overview

This repository contains the code and resources for a feature engineering assignment focused on audio analysis using multiple audio files. The main objective of this assignment is to apply various audio feature extraction techniques using the `librosa` library in Python on 5 different audio files.

## Table of Contents

- [Requirements](#requirements)
- [Audio File](#audio-file)
- [Colab Notebook](#colab-notebook)
- [Features Extracted](#features-extracted)
- [Quick Summary of Steps](#quick-summary-of-steps)
- [Usage](#usage)

## Requirements

- Python 3.x
- `librosa`
- `numpy`
- `matplotlib`

You can install the required libraries using pip:

```bash
!pip install librosa numpy matplotlib
```

## Audio File

The audio files used for this assignment include the following:

1. **1 Kepler Star KIC12268220C.mp3**
2. **2 Kepler Star KIC7671081B.mp3**
3. **3 NASA - Whistler Waves.mp3**
4. **4 Parker Solar Probe - Whistler Mode Waves 2.mp3**
5. **5 Juno Mission Europa Flyby.mp3**

Make sure these files are placed in the appropriate directory (same directory as the Colab notebook).

## Colab Notebook

The main analysis is performed in a Google Colab notebook. You can access the notebook at the following link:

[Feature Engineering Notebook](https://github.com/Mohib1402/CMPE255FeatureEngineering/blob/main/FeatureEngineering.ipynb)

## Features Extracted

In this assignment, the following audio features are extracted:

1. **Spectrogram**: A visual representation of the spectrum of frequencies in the audio signal as it varies with time.
2. **Mel-scaled Spectrogram**: A spectrogram that uses the Mel scale to mimic human hearing perception.
3. **Short-Time Fourier Transform (STFT)**: A sequence of Fourier transforms of a windowed signal.
4. **Beat Tracking**: Detection of the tempo and beats in the audio signal.
5. **Constant-Q Transform (CQT)**: A time-frequency representation that provides a better representation of musical notes.
6. **MFCCs**: Mel-Frequency Cepstral Coefficients used to represent the power spectrum of sound.

## Quick Summary of Steps

1. In this assignment, the following audio features are extracted for each of the 5 audio files:
2. Compute the Short-Time Fourier Transform (STFT) of the audio signal.
3. Generate the Mel-scaled spectrogram using the STFT.
4. Extract and display the spectrogram and Mel-scaled spectrogram.
5. Perform beat tracking to identify the tempo and beats.
6. Compute and visualize the Constant-Q Transform (CQT).
7. Calculate and display MFCCs (Mel-Frequency Cepstral Coefficients).

## Usage

1. Open the provided Google Colab notebook.
2. Ensure the audio files are accessible in the specified path.
3. Run the cells in the notebook to extract the features.
