# PyTorch

A collection of Jupyter notebooks covering the fundamentals of **PyTorch and deep learning**, progressing from tensors and basic model training to neural network classification, computer vision, and custom datasets.

## Contents

### 00. PyTorch Fundamentals

`00_PyTorch_Fundamentals.ipynb`

Covers the basics of working with PyTorch tensors:

- Creating tensors
- Random tensors, zeros and ones
- Tensor datatypes and attributes
- Tensor operations
- Matrix multiplication
- Tensor shape errors
- Aggregation operations
- Reshaping, stacking, squeezing and unsqueezing
- Tensor indexing
- NumPy and PyTorch
- Reproducibility
- Working with GPU/MPS devices

### 01. PyTorch Workflow

`01_pytorch_workflow_initial.ipynb`

Introduces a complete PyTorch workflow:

- Preparing and splitting data
- Building a neural network model
- Making predictions
- Training with loss functions and optimizers
- Creating training and testing loops
- Evaluating model performance
- Saving and loading models

### 02. Neural Network Classification

`02_PyTorch_classification.ipynb`

Explores classification with PyTorch, including:

- Binary classification
- Training and testing loops
- Logits, probabilities and predictions
- Model improvement
- Linear vs non-linear models
- ReLU and Sigmoid activation functions
- Multi-class classification
- Classification metrics

The notebook uses synthetic datasets to demonstrate classification concepts.

### 03. Computer Vision

`03_PyTorch_computer_vision(2).ipynb`

Applies PyTorch to image classification using **FashionMNIST**.

Topics include:

- Loading image datasets
- Dataset visualization
- `DataLoader`
- Building baseline neural networks
- Adding non-linearity
- Building a CNN with `Conv2d` and `MaxPool2d`
- Training and evaluation
- Comparing models
- Making predictions
- Confusion matrix
- Saving and loading the best-performing model

#### Model Results

| Model | Test Loss | Test Accuracy |
|---|---:|---:|
| FashionMNISTModelV0 | 0.4766 | 83.43% |
| FashionMNISTModelV1 | 0.6901 | 74.81% |
| FashionMNISTModelV2 (CNN) | **0.3241** | **88.39%** |

The CNN-based `FashionMNISTModelV2` achieved the best result in the recorded experiments.

### 04. PyTorch Custom Datasets

`04_PyTorch_custom_datasets.ipynb`

Covers working with image datasets and building custom dataset pipelines.

Topics include:

- Image data exploration
- Image transformations
- `ImageFolder`
- `DataLoader`
- Creating a custom `Dataset`
- Creating class mappings
- Data augmentation
- Building a custom `TinyVGG`
- Training and evaluation loops
- Comparing models with and without augmentation
- Making predictions on custom images

The image classification experiments use a **pizza, steak and sushi** dataset.

## Tools & Libraries

- Python
- PyTorch
- Torchvision
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Repository Structure

```text
pytorch/
│
├── 00_PyTorch_Fundamentals.ipynb
├── 01_pytorch_workflow_initial.ipynb
├── 02_PyTorch_classification.ipynb
├── 03_PyTorch_computer_vision(2).ipynb
├── 04_PyTorch_custom_datasets.ipynb
└── README.md
