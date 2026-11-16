# PyTorch Learning

A learning path through PyTorch, from the first linear models to a convolutional network for image classification.

The computer vision project that concludes this path has its own repository: [fashion-mnist-classification](https://github.com/sasam007/fashion-mnist-classification).

## Contents

- `circle_0.ipynb`, `linear_0.ipynb`, `linear_1.ipynb`, `linear_2.ipynb`, `linear_classification_0.ipynb`: regression and linear models
- `multiclass_0.ipynb`: multiclass classification
- `fashion_mnist_classification.ipynb`: first version of the FashionMNIST computer vision project (the cleaned-up version is in the repository above)
- `download.ipynb`: dataset download
- `helper_functions.py`: shared utility functions

## Installation

```bash
python -m venv .venv
source .venv/bin/activate
pip install torch torchvision scikit-learn matplotlib numpy requests tqdm jupyter
```

Datasets are not versioned: they are downloaded into `data/` on first run.
