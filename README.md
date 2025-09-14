# Cat vs Dog Classification using CNNs and Transfer Learning

This project focuses on classifying images of cats and dogs using deep learning.  
We train models both **from scratch** and using **transfer learning** with pre-trained weights.  
The performance of different CNN architectures is compared to identify the most effective model.

---

## 📌 Dataset
We use the [Cats vs Dogs dataset](https://www.kaggle.com/datasets/karakaggle/kaggle-cat-vs-dog-dataset) from Kaggle.

---

## 🧠 Models Implemented
1. **From Scratch**
   - MobileNet (trained without pre-trained weights)
   - LeNet
   - AlexNet
   - VGGNet
   - ResNet  

2. **With Transfer Learning (ImageNet weights)**
   - MobileNet
   - LeNet
   - AlexNet
   - VGGNet
   - ResNet  

---

## 📊 Results Summary
- **VGGNet (Transfer Learning)** achieved the **best performance** with ~93.8% accuracy.
- LeNet performed moderately (~75% accuracy).
- ResNet and AlexNet underperformed in this setup.
- MobileNet performed better with transfer learning compared to training from scratch.

---

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib, Seaborn

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/cat-vs-dog-transfer-learning.git
   ```

2. Install required dependencies:
    ```bash
   pip install -r requirements.txt
    ```

📌 Final Verdict

Among all tested models, VGGNet with transfer learning proved to be the most effective for the Cat vs Dog dataset, giving the best balance of accuracy and loss.

