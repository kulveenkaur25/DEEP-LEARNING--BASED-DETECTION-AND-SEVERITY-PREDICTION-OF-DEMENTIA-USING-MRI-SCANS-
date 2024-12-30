# Dementia Detection and Severity Prediction  

## Overview  
This project uses **Convolutional Neural Networks (CNN)** and **Grad-CAM** to classify dementia into four classes:  
1. No Dementia  
2. Very Mild Demented  
3. Mild Demented  
4. Moderately Demented  

Grad-CAM highlights critical brain regions, improving interpretability and aiding clinical diagnosis.  

## Dataset  
- **Source**: Kaggle  
- **Original Size**: 6,400 MRI images (imbalanced)  
- **Augmented Dataset**: Balanced 6,400 images using **DCGAN**  

## Results  
- **Best Model**: CNN  
  - Accuracy: 87%  
  - Precision (Macro Avg): 0.87  
  - Recall (Macro Avg): 0.87  
  - F1-Score (Macro Avg): 0.87  
- Grad-CAM visualizations show region-specific insights aiding explainability.  

## Challenges  
- Addressed class imbalance using DCGAN.  
- Overcame GPU limitations with Azure ML support.  

## Future Work  
- Explore advanced augmentation techniques like StyleGAN.  
- Combine image and non-image data for improved predictions.  
- Generalize the model for other neurodegenerative diseases.  

