# Digit Recognizer Dataset

## Overview

- **Name**: Digit Recognizer  
- **Source**: Kaggle — [Digit Recognizer Competition](https://www.kaggle.com/competitions/digit-recognizer/data)
- **Description**:  
  This dataset consists of grayscale images of handwritten digits (0–9). The goal is to build a classifier that correctly identifies which digit is in each image.

## Dataset Structure

| File | Rows | Columns / Image Size | Purpose |
|------|------|-----------------------|---------|
| `train.csv` | 42,000 | 785 (1 label column + 784 pixel columns) | Training data: each row has a label and corresponding 28×28 pixel values. |
| `test.csv`  | 28,000 | 784 pixel columns only | Test data: no label; used for evaluating predictions. |
| `sample_submission.csv` | 28,000 | 2 columns (ImageId, Label) | Format example for submission: IDs with predicted labels. |

## Data Fields

- **Label** (only in `train.csv`): integer in [0–9] representing the digit shown in the image.  
- **Pixel Columns**:  
  - `pixel0` through `pixel783` (or similarly named) — each represents a grayscale intensity value (0–255) of a pixel in the flattened 28×28 image, in row-major order.  
  - 0 typically means white/background, 255 means black/foreground (or vice versa, depending on preprocessing).

## Image Details

- **Type**: Grayscale  
- **Dimensions**: 28 × 28 pixels  
- **Flattening**: Images flattened into vectors (1×784) for storage in CSV; can be reshaped back into 28×28 for image tasks.

  ## 🔍 Sample Images from the Dataset

Here are some digits from the **training set** (reshaped from CSV data):
<img width="515" height="514" alt="image" src="https://github.com/user-attachments/assets/7320ebbb-8f48-44db-bf54-ab5187f17297" />
<img width="517" height="511" alt="image" src="https://github.com/user-attachments/assets/534eebc5-da7d-417c-ad38-ff763cf58699" />
<img width="514" height="511" alt="image" src="https://github.com/user-attachments/assets/eeb0ed7a-97bc-47d5-902f-7aba56548ab3" />
<img width="516" height="511" alt="image" src="https://github.com/user-attachments/assets/c8deeb8f-fbca-4eac-ac3d-f9bc637b783b" />


---

> Digit Recognizer. Kaggle Competition. Retrieved from https://www.kaggle.com/competitions/digit-recognizer/data

---
