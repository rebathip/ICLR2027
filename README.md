# Attenuate, Don't Drop: A Sign Entropy Approach to Weight Regularization

This repository contains the implementation and experiments for the paper:

**Attenuate, Don't Drop: A Sign Entropy Approach to Weight Regularization**

The proposed method uses Sign Entropy to identify Bayesian weights with uncertain directions and selectively attenuates their posterior parameters during training. The experiments evaluate the method on both classification and regression tasks using VGG16 and ResNet18 backbones.

## Notebooks

The repository contains four main experimental notebooks:

| Task | Backbone | Notebook |
|---|---|---|
| Classification | VGG16 | `classification_VGG16.ipynb` |
| Classification | ResNet18 | `classification_ResNet18.ipynb` |
| Regression | VGG16 | `regression_VGG16.ipynb` |
| Regression | ResNet18 | `regression_ResNet18_clean.ipynb` |



