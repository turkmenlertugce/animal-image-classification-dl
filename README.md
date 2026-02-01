# Animal Image Classification (CNN & Transfer Learning)
This project evaluates different CNN strategies to understand how architectural choices and training techniques affect model performance. Experiments focus on:

- **VGG16** and **ResNet50**
- Training from scratch vs. **transfer learning**
- **Learning rate tuning**
- **Data augmentation**
- **Regularization**

## Experiments Summary

- **VGG16 (from scratch):** Poor learning and low accuracy  
- **ResNet50 (from scratch):** Better performance but overfitting observed  
- **Transfer Learning (VGG16):** Faster convergence and higher accuracy  
- **Learning Rate Tuning:** Larger learning rate (0.01) improved convergence  
- **Data Augmentation:** Increased generalization and validation accuracy  
- **Regularization:** Reduced overfitting but slightly lowered performance  

## Final Models

### Best Model
**Transfer Learning (VGG16) + LR = 0.01 + Data Augmentation**

- Validation Accuracy: **0.975**
- Best generalization and stability

### Alternative Model
**Transfer Learning + LR = 0.01 + Data Augmentation + Regularization**

- Validation Accuracy: **0.943**
- More stable but lower peak performance

## Tools

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
