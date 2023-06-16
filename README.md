# Frequency-Analysis-and-Denoising-of-Voice-Signals
The project involves applying the Discrete Fourier Transform (DFT) to identify the frequencies present in the recorded voice signals.  Additionally, a denoising algorithm is implemented to filter out unwanted noise from the recorded signals.
# Voice Signal Analysis Project

This project focuses on analyzing voice signals using the Discrete Fourier Transform (DFT) and implementing denoising techniques. The goal is to explore the frequencies present in recorded voice signals and apply a denoising algorithm to remove unwanted noise.

## Problem Statement

The project aims to analyze voice signals captured while participants speak specific sequences of alphabets. The recorded voice signals are collected at different sampling frequencies (500Hz, 2000Hz, and 16000Hz) for four members of the group and sentences. The objective is to identify the frequencies present in each recording and observe variations across sentences, group members, and sampling rates.

## Methodology

The project is divided into two main parts: frequency analysis and denoising.

1. Frequency Analysis:
   - The recorded voice signals are loaded and processed using the DFT algorithm.
   - A custom implementation of the DFT is used to calculate the frequencies present in each signal.
   - The magnitude spectrum of each signal's DFT is plotted to visualize the frequency components.

2. Denoising:
   - The recorded voice signals are loaded and mixed with Gaussian noise to simulate real-world scenarios.
   - A convolution-based denoising algorithm is implemented using a predefined kernel.
   - The noisy signals are convolved with the kernel to obtain denoised signals.
   - The denoised signals are saved as separate WAV files for further analysis.

## Findings

By analyzing the magnitude spectrum of the recorded voice signals, the project aims to uncover interesting findings regarding the frequencies present in the signals across different conditions. The variations observed in the frequency components will provide insights into how sentence structures, group members, and sampling rates affect voice signal characteristics.

## Requirements

To run the code and reproduce the results, the following dependencies are required:

- numpy
- librosa
- matplotlib
- scipy
