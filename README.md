# Opencv_imageClassification_Kaggle

Image Classification from Scratch — CNN Training Journey
A project documenting the full process of building and training a Convolutional Neural Network from scratch for a 4-class animal image classification task (cow, elephant, horse, spider), achieving 88%+ validation accuracy with only ~4,000 training images and a ~150k parameter model.
The repository covers the complete experimentation journey including:

Debugging a broken training pipeline (rescaling bug, disconnected layers)
Reducing a 1.5M parameter model to 150k parameters without losing performance
Understanding and fixing overfitting through dropout, batch normalization and data augmentation
Systematic experiment tracking and iterative improvement
Achieving 85%+ Kaggle test accuracy training entirely from scratch

Key learnings: more parameters do not mean better generalization, small validation sets cause noisy curves, and systematic one-change-at-a-time experimentation is essential for meaningful progress.
Stack: Python, TensorFlow/Keras, Google Colab

