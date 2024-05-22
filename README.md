# Simple OCR Deep Learning example  
This repository contains a very simple example on OCR detection of license plate
codes using a Neural Network based on this example: 
- https://keras.io/examples/vision/captcha_ocr/#inference

The dataset used for this was this one:
- https://www.kaggle.com/datasets/nickyazdani/license-plate-text-recognition-dataset

## Dataset samples
![Training](readme_images/dataset.png)

## Model architecture
The base model architecture:

![Training](readme_images/architecture.png)

# Results
No image augmentations were used for the model that gave these results.

## Training metrics
![Training](readme_images/training.png)


## Predictions
Some predictions on the test set:

![Training](readme_images/predictions.png)


## Overall Performance:

- **Character Accuracy**: 0.956989247311828
- **Average Precision**: 0.965224721750613  
- **Average Recall**: 0.956989247311828  
- **Average F1**: 0.9587213522697393

## Classification Report:

| Character | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
|   0   |   1.00    |  0.94  |   0.97   |
|   1   |   0.95    |  1.00  |   0.97   |
|   2   |   0.93    |  0.93  |   0.93   |
|   3   |   1.00    |  1.00  |   1.00   |
|   4   |   1.00    |  1.00  |   1.00   |
|   5   |   1.00    |  1.00  |   1.00   |
|   6   |   0.94    |  1.00  |   0.97   |
|   7   |   1.00    |  0.94  |   0.97   |
|   8   |   0.83    |  0.83  |   0.83   |
|   9   |   1.00    |  1.00  |   1.00   |
|   B   |   1.00    |  1.00  |   1.00   |
|   C   |   1.00    |  0.67  |   0.80   |
|   D   |   0.50    |  1.00  |   0.67   |
|   E   |   1.00    |  1.00  |   1.00   |
|   F   |   1.00    |  1.00  |   1.00   |
|   H   |   1.00    |  1.00  |   1.00   |
|   J   |   1.00    |  1.00  |   1.00   |
|   K   |   1.00    |  1.00  |   1.00   |
|   L   |   1.00    |  1.00  |   1.00   |
|   M   |   1.00    |  1.00  |   1.00   |
|   N   |   0.75    |  1.00  |   0.86   |
|   P   |   1.00    |  1.00  |   1.00   |
|   Q   |   1.00    |  1.00  |   1.00   |
|   R   |   1.00    |  1.00  |   1.00   |
|   S   |   1.00    |  1.00  |   1.00   |
|   T   |   1.00    |  1.00  |   1.00   |
|   U   |   0.67    |  0.50  |   0.57   |
|   V   |   1.00    |  1.00  |   1.00   |
|   W   |   1.00    |  1.00  |   1.00   |
|   X   |   1.00    |  1.00  |   1.00   |
|   Y   |   1.00    |  1.00  |   1.00   |
|   Z   |   1.00    |  0.67  |   0.80   |
---
