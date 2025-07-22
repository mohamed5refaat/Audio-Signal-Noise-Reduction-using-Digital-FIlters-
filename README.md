# Digital Signal Processing: Noise Addition and Filtering

This project demonstrates basic concepts in **Digital Signal Processing (DSP)** using Python. It generates a clean audio signal, adds noise (white noise and 50Hz hum), and prepares the noisy audio for further processing such as filtering and analysis.

## 📌 Features

- Generation of a synthetic clean signal (sine waves at 300Hz and 1000Hz)
- Addition of:
  - White noise
  - 50Hz hum (common electrical interference)
- Saving the noisy signal as a WAV file
- Imports functions for:
  - Spectrogram visualization
  - Filtering (Butterworth)
  - Error analysis (MSE)

## 🧰 Requirements

To run the notebook, make sure you have the following Python libraries installed:

```bash
pip install numpy matplotlib soundfile scipy scikit-learn
