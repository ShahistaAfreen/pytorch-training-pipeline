# PyTorch Training Pipeline  

This project demonstrates how to build and train a simple neural network **from scratch** using the **Breast Cancer dataset** and PyTorch’s autograd functionality.  

The goal is to provide a minimal working example for:  
- Preparing data for training  
- Implementing a neural network manually (without `nn.Module`)  
- Using autograd for backpropagation  
- Training with binary cross-entropy loss  
- Evaluating model performance  

---

##  Dataset 
It is a binary classification dataset with 30 features and a target variable (malignant or benign).  
---

---
## Results

During training, the loss decreases steadily as expected:

Epoch: 1, Loss: 0.5262
Epoch: 5, Loss: 0.4633
Epoch: 10, Loss: 0.3919
Epoch: 15, Loss: 0.3288
Epoch: 20, Loss: 0.2752
Epoch: 25, Loss: 0.2318


Final model accuracy: 52.8%
---
## Future Improvements

Improve accuracy by adding multiple layers

Use train/validation split with evaluation metrics

Plot training curves (loss vs epochs, accuracy vs epochs)

Experiment with optimizers (torch.optim)
