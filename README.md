# Transformer Networks for Mining Site Detection
We aim to tackle detecting mining activities by developing a robust technology for detecting mining sites using optical satellite imagery from Sentinel-2. By leveraging the capabilities of Vision Transformer (ViT) models, we classify images to identify the presence or absence of mining sites. The primary objective is to automate the detection process, providing a reliable tool for real-time monitoring of mining activities."

# Summary of Approach
Stratified Group K-Fold Cross validation, feature engineering, data augmentations and vison transformer model. All models are pretrained models and they are fine-tuned on the dataset. Made use of Google Colab GPU.

architectures
# Model Architecture

Timm's MaxViT model

# Data Augmentations
The following augmentations are included:

1. Rotation
2. Vertical flipping
3. Horizontal flipping
   
# Common Configuration
The following configurations is applied:

1. Cyclic Learning
2. FP16 precision
3. Label Smoothing
4. Weight Decay

