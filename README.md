# fracture-detection
A deep learning-based computer vision project for detecting bone fractures from X-ray images. The model is trained using MobileNetV2 and provides accuracy reports, confusion matrix, and visualization graphs.
This project implements a Computer Vision approach for bone fracture detection using X-ray images. It leverages Transfer Learning with MobileNetV2 to classify whether a bone is Fractured or Not Fractured.

Features

Preprocessing of X-ray dataset using ImageDataGenerator
Transfer Learning with MobileNetV2
Training visualization (Accuracy & Loss graphs)
Performance evaluation with Confusion Matrix and Classification Report
Single image prediction (upload your own X-ray to test fracture detection)

x-ray/
│── train/
│   ├── Fractured/
│   ├── Not Fractured/
│
│── val/
│   ├── Fractured/
│   ├── Not Fractured/
│
│── sample_test/
│   ├── fracture1.jpg
│   ├── normal1.jpg

predict single image

predict_image("x-ray/sample_test/fracture1.jpg", model)
[Fracture_Detection.ipynb](https://github.com/user-attachments/files/22196352/Fracture_Detection.ipynb)
