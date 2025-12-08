# Uncertainty modulated reward prediction error in VTA

## Project Overview
This project identifies putative dopaminergic neurons in Ventral Tegmental Area (VTA) to investigate how they encode reward prediction error (RPE) during a visual discrimination task. While the subject mice is overtrained and the general task structure is stable, this project leverages trial by trial variability in visual stimulus contrast to introduce varying levels of perceptual uncertainty and reward expectation.
The primary goal is to characterize how VTA encodes outcome related signals under different levels of usensory confidence, providing insight into how the brain maintains flexible reward signaling even in stable environments.

## Content
Task Structure: A visual discrimination task where mice are required to turn a wheel toward a visual stimulus (left or right) to receive a sugar water reward.

Independent Variable: Stimulus Contrast. The contrast varies trial-by-trial, creating a spectrum of perceptual uncertainty.

Dataset:

Source: International Brain Lab (IBL) public dataset.

Data: Electrophysiological data.

Format: ALF (Alyx Lab Format).

Region of Interest: Ventral Tegmental Area (VTA).

Subjects: Mice

## Analysis Pipeline
The Python notebook implements a statistical pipeline to isolate and quantify single-neuron responses.

1. Data Preprocessing and Trial Selection
2. Population-Level Modeling
3. Single-Neuron Statistical Analysis
4. Visualization

## Requirements
The analysis requires a standard Python 3 scientific stack: numpy, pandas, scipy, statsmodels, matplotlib, tabulate.
