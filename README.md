# CS342-wine-classifier

Authors: Ryan Gahagan (rg32643) and Dustan Helm (dbh878)

This is the CS 342: Neural Networks final project.
In this project, we will build a feed-forward neural network
to predict the quality of a wine given attributes about its
chemical composition using PyTorch.

The data set that we are using and the paper that we are
basing our model on are both from the following source:

```
  P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. 
  Modeling wine preferences by data mining from physicochemical properties.
  In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.
```

If you'd like, you can find the data set [here](https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/)
and you can find the paper [here](https://www.sciencedirect.com/science/article/abs/pii/S0167923609001377?via%3Dihub).

We will also perform several computational experiments in order to best
tune our hyperparameters and analyze our model.

## Setup

Ideally, this code should just run out of the box in Jupyter-Notebook.
To run it yourself, simply clone this repository and make sure you have
the following things installed:
- Jupyter-Notebook
- Python 3
- PyTorch
- torchvision

