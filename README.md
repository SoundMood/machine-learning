# machine-learning

**SoundMood** is an innovative application that provides personalized music recommendations based on a user's emotional state, as inferred from facial expressions. This repository focuses on the facial expression classification module of the system, developed using a custom **Convolutional Neural Network (CNN)** implemented in **TensorFlow**.

## Dataset
The dataset originally uses [RAF-DB (Real-world Affective Faces Database)](https://www.kaggle.com/datasets/shuvoalok/raf-db-dataset), which is a dataset for facial expression recognition. This dataset consists of various facial images with different expressions taken from real situations.

In this project, the RAF-DB dataset has been modified to use only **5 emotion classes**, namely: **happy**, **sad**, **angry**, **surprised**, and **neutral**.

### Dataset Distribution

| Class      | Train Quantity | Test Quantity |
|------------|----------------|---------------|
| Happy      | 4772           | 1185          |
| Sad        | 1982           | 478           |
| Angry      | 699            | 162           |
| Surprised  | 1290           | 329           |
| Neutral    | 2525           | 680           |

![Dataset Distribution](https://drive.google.com/uc?export=view&id=1rXi9V0tYZyeGo5gz0u0ybPtwTChEMIL8)

### Dataset Sample
The dataset example is shown below:
![Sample data](https://drive.google.com/uc?export=view&id=1h9AV5P6VpX-r07mAFc3Nepmm6FPViqoG)

## Training and Validation Result
- **Training Accuracy**: 99%
- **Validation Accuracy**: 88%

## Classification Metrics

| Class      | Precision | Recall | F1-Score | Support |
|------------|-----------|--------|----------|---------|
| Angry      | 0.88      | 0.77   | 0.82     | 162     |
| Happy      | 0.94      | 0.94   | 0.94     | 1185    |
| Neutral    | 0.82      | 0.86   | 0.84     | 680     |
| Sad        | 0.84      | 0.82   | 0.83     | 478     |
| Surprised  | 0.89      | 0.84   | 0.86     | 329     |
| **Accuracy** |          |        |  **0.88**| **2834**|
| **Macro avg** | **0.87** | **0.85** | **0.86** | **2834**|
| **Weighted avg** | **0.88** | **0.88** | **0.88** | **2834**|

## Prediction Example

Below is an example of the prediction result:

![image](https://github.com/user-attachments/assets/c4bf1253-6047-4e80-9993-a27b6c9fe25c)

