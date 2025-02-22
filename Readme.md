# Fine-Tuning ResNet50 for Image Classification

## 📌 Project Overview
This project fine-tunes a **pre-trained ResNet50 model** for image classification. The model is trained on a custom dataset and modified to improve its classification accuracy. The trained model is saved and can be used for inference on new images.

## 📂 Dataset Structure
Ensure your dataset is structured as follows:
```
dataset/
├── train/
│   ├── class_1/  (e.g., cats)
│   ├── class_2/  (e.g., dogs)
├── validation/
│   ├── class_1/
│   ├── class_2/
```
Each subfolder contains images related to that class.

## ⚙️ Features
- **Pretrained Model**: Uses ResNet50 with ImageNet weights.
- **Fine-Tuning**: Unfreezes the last 10 layers for better learning.
- **Data Augmentation**: Enhances generalization with transformations.
- **Learning Rate Scheduling**: Improves convergence.
- **Model Saving**: Saves the trained model in `.keras` format.

## 🚀 Installation & Setup
1️⃣ **Clone the Repository**
```bash
git clone https://github.com/YOUR_USERNAME/ResNet50-Fine-Tuning.git
cd ResNet50-Fine-Tuning
```

2️⃣ **Install Dependencies**
```bash
pip install tensorflow keras
```

## 🔧 How to Train the Model
Run the script to train the model:
```bash
python fine_tune_resnet.py
```
Or, if using Jupyter Notebook:
```python
!jupyter notebook fine_tune_resnet.ipynb
```

## 💾 Model Output
After training, the model is saved as:
```
fine_tuned_resnet50.keras
```

## 📤 Uploading to GitHub
To push this project to GitHub, follow these steps:
```bash
git init
git add .
git commit -m "Initial commit - Fine-tuned ResNet50 model"
git remote add origin https://github.com/YOUR_USERNAME/ResNet50-Fine-Tuning.git
git push -u origin master
```

## 📄 License
This project is licensed under the MIT License. Feel free to use and modify it.

---
📩 **For any questions or issues, feel free to open an issue or contact me!**

