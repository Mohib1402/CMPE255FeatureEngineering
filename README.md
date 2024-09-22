# Audio Feature Engineering Assignment

## Overview

This repository contains the code and resources for a feature engineering assignment focused on audio analysis. The main objective of this assignment is to apply various audio feature extraction techniques using the `librosa` library in Python.

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
pip install librosa matplotlib
```

## Audio File

The audio file used for this assignment is **Main_kepler_star_KIC12268220C.mp3**, sourced from NASA's website. This file is located in the same directory as the notebook in Google Colab.

## Colab Notebook

The main analysis is performed in a Google Colab notebook. You can access the notebook at the following link:

[Feature Engineering Notebook](LINK_TO_YOUR_COLAB_NOTEBOOK)

## Features Extracted

In this assignment, the following audio features are extracted:

1. **Spectrogram**: A visual representation of the spectrum of frequencies in the audio signal as it varies with time.
2. **Mel-scaled Spectrogram**: A spectrogram that uses the Mel scale to mimic human hearing perception.
3. **Short-Time Fourier Transform (STFT)**: A sequence of Fourier transforms of a windowed signal.
4. **Beat Tracking**: Detection of the tempo and beats in the audio signal.
5. **Constant-Q Transform (CQT)**: A time-frequency representation that provides a better representation of musical notes.

## Quick Summary of Steps

1. Load the audio file into the Colab environment.
2. Compute the Short-Time Fourier Transform (STFT) of the audio signal.
3. Generate the Mel-scaled spectrogram using the STFT.
4. Extract and display the spectrogram and Mel-scaled spectrogram.
5. Perform beat tracking to identify the tempo and beats.
6. Compute and visualize the Constant-Q Transform (CQT).

## Usage

1. Open the provided Google Colab notebook.
2. Ensure the audio file is accessible in the specified path.
3. Run the cells in the notebook to extract the features.
