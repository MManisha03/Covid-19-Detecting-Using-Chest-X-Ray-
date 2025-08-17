# COVID-19 Detection Using CNN and VGG16 on Chest X-Ray Images
📌 Abstract

This study investigates the efficacy of artificial intelligence (AI) in detecting COVID-19 through chest X-ray analysis. Utilizing a Convolutional Neural Network (CNN) and VGG16 (transfer learning), the model demonstrates promising accuracy, sensitivity, and specificity in distinguishing COVID-19 positive and negative cases. Evaluation against established diagnostic standards, including RT-PCR results, underscores its potential as a valuable tool, especially in resource-limited settings.

Keywords: CNN, VGG16, COVID-19, Chest X-ray, RT-PCR, Deep Learning

# 🏥 Introduction

The COVID-19 pandemic highlighted the need for fast, reliable, and cost-effective diagnostic methods. While RT-PCR remains the gold standard, it faces limitations in accessibility and turnaround time. This project integrates AI with chest radiography to provide a rapid screening solution.

Dataset: Chest X-ray images (COVID-19 positive & negative cases)

Goal: Automate COVID-19 detection using deep learning models

Approach: Compare CNN vs. VGG16 models for classification accuracy

# 📚 Literature Review

Previous studies demonstrate the effectiveness of deep learning in medical imaging:

Ajaykumar Dhamireddy et al.: Compared CNN, VGG16, and MobileNet, achieving ~96% accuracy.

Harsh Agrawal: Achieved 96% accuracy using transfer learning for pneumonia detection.

Zakariah et al.: ResNet models achieved 98.34% accuracy.

Sohaib Asif et al.: InceptionV3 with transfer learning achieved >98% accuracy.

This project builds on such findings, improving COVID-19 detection accuracy using CNN and VGG16.

# 📊 Dataset & Tools

Dataset Source: Kaggle (COVID-19 Chest X-ray dataset)

Categories:

Normal (Healthy cases)

Pneumonia/COVID-19 (Positive cases)

Tools Used: Google Colab

Libraries: numpy, pandas, scipy, opencv, tensorflow, keras

# ⚙️ Methodology
🔹 Preprocessing

Converted images to grayscale

Resized and normalized images

Augmented dataset for better generalization

🔹 Models

1. Convolutional Neural Network (CNN)

Convolutional, pooling, flatten, and dense layers

Activation: ReLU

Pooling: MaxPooling

Achieved 93.6% accuracy

2. VGG16 (Transfer Learning)

Pre-trained on ImageNet

Fine-tuned classifier layers

Achieved 98.6% accuracy

# 📈 Results
Model	Accuracy	Previous Works Accuracy	Our Accuracy
CNN	68%	93.6%	✅ Improved
VGG16	82%	98.6%	✅ Improved

CNN Accuracy: 93.6%

VGG16 Accuracy: 98.6% (best performing)

📊 Example Outputs:

Accuracy & loss plots per epoch

Random predictions on test images
