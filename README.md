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

## Classification Experiments

The classification experiments are performed on the Fashion-MNIST dataset.

The corresponding notebooks are:

```text
classification_VGG16.ipynb
classification_ResNet18.ipynb

## Regression Experiments

The regression experiments evaluate the proposed Sign Entropy guided attenuation method on the **UTKFace age estimation task**.

Two backbone architectures are evaluated:

- VGG16
- ResNet18

The corresponding notebooks are:

```text
regression_VGG16.ipynb
regression_ResNet18_clean.ipynb
