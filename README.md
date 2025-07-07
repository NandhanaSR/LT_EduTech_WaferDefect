# LT_EduTech_WaferDefect
1. AIM OF THE PROJECT

The aim of this project is to detect semiconductor wafer defects using Convolutional Neural Networks (CNNs). The objective is to classify different failure patterns such as Center, Donut, Scratch, and other defect types using image-based deep learning techniques.

2. UNIQUENESS/DIFFERENTIATOR TRIED OUT IN THE PROJECT

This project implements a CNN built using Keras to process wafer map images directly. The images are processed through multiple convolution and pooling layers to learn spatial features effectively. A custom train-validation split was created using actual defect image folders.

3. INFERENCE

The CNN model was able to accurately classify wafer defects, with a steadily improving validation accuracy across epochs. The model demonstrated strong generalization ability with minimal overfitting, indicating its suitability for real-time wafer inspection scenarios in the semiconductor industry.

4. METRICS OF THE PROJECT

Model accuracy after training for 10 epochs:

* Training Accuracy: ~0.98

* Validation Accuracy: ~0.95

* Loss Curves: Showed proper convergence with decreasing loss and increasing accuracy across epochs



Additional metrics calculated:

* Confusion Matrix (per class breakdown)

* F1 Score

* Precision

* Recall


📁 Dataset Source:

WM811k Wafer Map Dataset from Kaggle

Used the image-based .zip version instead of the provided .pkl file for clarity and ease of processing.

🔗 https://www.kaggle.com/datasets/paulbassaler/defect-detection-in-wafer-bin-maps

