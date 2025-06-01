# Weather Classification with CNN, Residual Networks & Transfer Learning

**Image classification of 11 weather conditions using custom CNNs and transfer learning with ResNet101 & EfficientNetB7.**

---

## Problem Statement

Predict the weather type from an input image across 11 categories:  
`dew, fog/smog, frost, glaze, hail, lightning, rain, rainbow, rime, sandstorm, snow`

Dataset: 6862 labeled images (balanced)

## Models Implemented

### 1 - Simple CNN  
Sequential model built from scratch using basic Conv2D and MaxPooling layers  
`Homework3_1.ipynb`

### 2 - CNN with Residual Blocks + Data Augmentation  
Custom architecture with manually coded residual blocks (like in ResNet)  
+ extensive image augmentation (`ImageDataGenerator`)  
`Homework3_2.ipynb`

### 3 - Transfer Learning  
Fine-tuned models pretrained on ImageNet:
- **ResNet101**
- **EfficientNetB7**  
`Homework3_EfficientNetB7.ipynb` and `Homework3_ResNet101.ipynb`

## Evaluation Metrics

- Accuracy (train / val)
- Loss curves
- Model comparison
- (Optional) Confusion matrix, per-class breakdown

## Files

| File                             | Description                                           |
|----------------------------------|-------------------------------------------------------|
| `CNN.ipynb`              | Baseline CNN model                                    |
| `Advanced_CNN.ipynb`              | Residual CNN + Augmentation                           |
| `EfficientNetB7.ipynb` | Transfer Learning with EfficientNetB7 + ResNet101     |
| `ResNet101.ipynb`      | Alternative implementation or cross-validation        |
| `instructions.pdf`              | Project description and dataset overview              |

---

## Author

**Moncef Berkoun**  
🎓 Double Master's Degree in AI Engineering and Technological Entrepreneurship – UTBM  
🔗 [LinkedIn](https://www.linkedin.com/in/moncef-berkoun/)  
📧 moncef.berkoun@gmail.com
