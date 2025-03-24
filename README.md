# EEG Emotion Classification

This repository contains Python scripts in a Jupyter Notebook aimed at building a classification model using sample filtered EEG data. The primary goal is to predict emotional states (Negative, Neutral, Positive) of an individual based on feature-extracted EEG signals. All the implementation details and analysis are contained within the notebook [`eeg_analysis.ipynb`](eeg_analysis.ipynb).

## File Directory
```
eeg-emotion-classification/
├── data/
│   └── emotions.csv
├── models/
│   └── emotion_classifier_model.pth
├── eeg_analysis.ipynb
├── README.md
└── .gitignore
```

## Purpose
The purpose of this program is to explore EEG-based emotion classification using a Recurrent Neural Network (RNN). The dataset has been preprocessed with extracted features such as statistical metrics and FFT values using [these scripts](https://github.com/jordan-bird/eeg-feature-generation).

## Data Citation
The data used in this project belongs to the following studies:

1. J. J. Bird, L. J. Manso, E. P. Ribiero, A. Ekart, and D. R. Faria, “A study on mental state classification using eeg-based brain-machine interface,” in 9th International Conference on Intelligent Systems, IEEE, 2018.

2. J. J. Bird, A. Ekart, C. D. Buckingham, and D. R. Faria, “Mental emotional sentiment classification with an eeg-based brain-machine interface,” in The International Conference on Digital Image and Signal Processing (DISP’19), Springer, 2019.
