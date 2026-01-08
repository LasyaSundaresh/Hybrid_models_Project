# Hybrid_models_Project
This project includes saved hybrid deep learning models built using transfer learning techniques
🍃 Fruit Leaf and Medicinal Leaf Classification
🎯 Project Objective

The objective of this project is to classify fruit leaves and medicinal leaves using deep learning techniques. Accurate classification helps in plant identification, agricultural monitoring, and medicinal plant recognition.

🧠 Model Used
🔹 Hybrid Deep Learning Model

This project uses a hybrid transfer learning approach by combining:

Model	Role
VGG16	Extracts texture, shape, and edge features
VGG19	Captures deeper and more complex visual patterns

The extracted features from both models are combined to improve classification accuracy.

🗂️ Dataset

Images of fruit leaves (e.g., mango, banana, apple, etc.)

Self created image dataset of medicinal leaves 

Dataset is preprocessed using resizing, normalization, and augmentation


models/
 ├── hybrid_vgg16_vgg19_leaf_classifier.h5
