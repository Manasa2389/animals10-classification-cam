# Animal Classification using ResNet18 + CAM

This project classifies images into 10 animal categories using the Animals-10 dataset.  
It uses Transfer Learning with ResNet18 and Explainable AI using Class Activation Maps (CAM).

## Features
- ResNet18 Transfer Learning
- 10 Animal Classes (dog, cat, horse, elephant...)
- Google Colab Training
- CAM Heatmaps (model attention visualization)
- Saved PyTorch model

## Files
- animals10_resnet18.pth → trained model
- project.ipynb → full code
- heatmap examples → model explainability

## How it works
1. Load data and preprocess  
2. Freeze ResNet18 layers  
3. Train last layer  
4. Predict animal  
5. Generate CAM heatmap (explainability)
