# EEG Eye State Classification

A machine learning project that predicts whether a person's eyes are open or closed from 14 EEG sensor measurements.

## Project goal

Build and evaluate reproducible baseline models for EEG eye-state classification.

## Dataset

UCI Machine Learning Repository

EEG Eye State

Dataset ID: 264

14 EEG features

14,980 observations

Target:

0 = eyes open

1 = eyes closed

License: CC BY 4.0

## Models

1. Logistic Regression
2. Random Forest

## Evaluation

Accuracy

Precision

Recall

F1 score

Confusion matrix

Feature importance

## Run the notebook

Open the notebook directly in Google Colab:

https://colab.research.google.com/github/leehanpark/BARK1/blob/main/eeg_eye_state_classification.ipynb

Or install the requirements locally:

```bash
pip install -r requirements.txt
jupyter notebook eeg_eye_state_classification.ipynb
```

## Files

`eeg_eye_state_classification.ipynb`

Complete machine learning workflow

`requirements.txt`

Required Python packages

## Main limitation

The dataset is one continuous chronological EEG recording. A random split may overestimate real-world performance because nearby observations can be highly similar.

## Next improvement

Use chronological splitting or time-series cross-validation.

## Author

Leehan Park

Mathematics undergraduate interested in AI and computational neuroscience.

## Dataset citation

Roesler, O. (2013). EEG Eye State [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C57G7J
