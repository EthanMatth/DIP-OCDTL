# DIP_OCDTL
Digital Image Processing final project. Classifying Optical Coherence Tomograph images using Convalutional Neural Networks

# Files:
OCTL.ipynb: Main Colab file that accesses kaggle dataset and sets up CNN and ResNet models
README.md: You're reading it

# AI Disclaimer
Gemini was used to assist in the creation of the Custom CNN model

# Processes
1. Initialize main libraries to be used
2. Load dataset from Kaggle
3. Resize images to 244 x 244
4. Segment dataset for Train (75%), Validate (15%), and Test (15%)
5. Define Custom CNN model
6. Define Training Parameters (cross entropy loss and adam optimizer with lr = 0.01)
7. Train model with 10 epochs
8. Visualize results with F1 scores and confusion matrix
9. Initialize ResNet model
10. Train ResNet with 10 epochs
11. Visualize results with F1 scores and confusion matrix