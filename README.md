# HMS - Harmful Brain Activity Classification

## Overview
This repository contains the code for the "HMS - Harmful Brain Activity Classification" Kaggle competition. The goal of the competition is to classify seizures and other patterns of harmful brain activity in critically ill patients based on EEG (Electroencephalogram) signals.

## Competition Description
The competition involves classifying EEG signals into one of six classes: Seizure, LPD (Lateralized Periodic Discharges), GPD (Generalized Periodic Discharges), LRDA (Lateralized Rhythmic Delta Activity), GRDA (Generalized Rhythmic Delta Activity), and Other.

## Contents
- `train.csv`: CSV file containing training data information, including EEG and spectrogram file paths, labels, and patient IDs.
- `test.csv`: CSV file containing test data information, including EEG and spectrogram file paths and IDs.
- `train_eegs/`: Directory containing training EEG signals in Parquet format.
- `train_spectrograms/`: Directory containing spectrograms of training EEG signals in Parquet and NumPy formats.
- `test_eegs/`: Directory containing test EEG signals in Parquet format.
- `test_spectrograms/`: Directory containing spectrograms of test EEG signals in Parquet and NumPy formats.
- `sample_submission.csv`: Sample submission CSV file for Kaggle competition.
- `README.md`: This file, providing an overview of the repository and its contents.
- Other Python scripts containing code for data processing, model training, and evaluation.

## Requirements
- Python (>=3.6)
- TensorFlow (>=2.0)
- Keras (>=2.3)
- OpenCV (>=4.0)
- Pandas (>=1.0)
- NumPy (>=1.18)
- Matplotlib (>=3.0)

