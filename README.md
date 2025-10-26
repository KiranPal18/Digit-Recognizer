# Implementation of CNN Models from Scratc

This project presents an implementation of a Convolutional Neural Network (CNN) developed entirely from scratch using PyTorch for the task of handwritten digit classification.  
The model is trained and evaluated on the [Kaggle Digit Recognizer dataset](https://www.kaggle.com/competitions/digit-recognizer), which consists of grayscale images of digits (0–9).  
The primary objective of this work is to understand the fundamental concepts of CNN architecture, training, and evaluation without relying on pre-trained networks.

---

### This project includes:
```bash
* Custom CNN implementation
* ResNet-based implementation
* Dataset and Dataloader setup
* Training and Validation pipelines
* Result visualization and submission generation
```

---

## Implementations
1. **Simple_CNN.ipynb** – SImple and Custom CNN implementation.  
2. **ResNet.ipynb** – ResNet-based model that improves feature learning and achieves higher accuracy.

---

### Result:
-Simple CNN Model Accuracy : 98.21%      
-ResNet Model Accuracy  : 98.78%

---

### Future Improvements
- Experiment with deeper ResNet variants or lightweight CNNs.  
- Apply data augmentation and learning rate scheduling for further gains.  
- Develop a simple interface for users to draw and predict digits in real time.
