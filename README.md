# 🔢 Digit Recognizer  

This project is a CNN-based handwritten digit classifier trained on the [Kaggle Digit Recognizer dataset](https://www.kaggle.com/competitions/digit-recognizer/data).  
The dataset contains **28×28 grayscale images** of digits `0–9` in CSV format. 

### Example Images
<img width="514" height="510" alt="image" src="https://github.com/user-attachments/assets/af4570c8-b472-4efe-b764-feba7604a0f1" />
<img width="514" height="509" alt="image" src="https://github.com/user-attachments/assets/5256b459-6616-406a-b4f4-a7d5a49a6e3d" />
<img width="515" height="516" alt="image" src="https://github.com/user-attachments/assets/4b23cc5d-17f4-401c-bcc3-6178384b5d34" />


---

## 🧠 Model  
- Framework: **PyTorch**  
- Architecture: Simple **CNN** (Conv → Pool → Dropout → Dense → Softmax)  
- Optimizer: **Adam**  
- Loss: **CrossEntropyLoss**  
- Epochs: **15**  

---

## 📊 Training Results  

- Final **Train Accuracy**: 98.49%  
- Final **Validation Accuracy**: 98.21%  

Training converged smoothly, with both training and validation accuracy exceeding **98%**.  

### 📉 Training vs Validation Loss  
<img width="717" height="560" alt="image" src="https://github.com/user-attachments/assets/4651ad0a-2213-454d-8f97-541dd7031707" />


---
## 🔮 Future Work  
Some potential areas for improvement include:  

1. **Model Compression** – Apply pruning, quantization, or knowledge distillation techniques to make the model lightweight and suitable for deployment on mobile or edge devices.  

2. **Interactive Applications** – Extend this work into a real-time digit recognition tool where users can draw digits using a mouse or touchscreen and instantly receive predictions.  

---
