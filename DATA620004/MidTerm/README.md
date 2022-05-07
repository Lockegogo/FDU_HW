# MidTerm Project

Code for MidTerm PJ  of course `DATA620004` (Neural Networks and Machine Learning) at Fudan University in 2022 spring. 

## Require

* Python 3.8
* Numpy 1.19.2

## Code

* `data.py`: DatasetLoader class, including loading of MNIST datasets, partitioning of training and validation sets, and generation of small batch samples.
* `model.py`:  TwoLayerNN class, including activation function, forward propagation, backward propagation, loss and gradient calculation, parameter update (SGD), learning rate reduction, training function and test function, etc.
* `train.py`: Model training code for training and saving models.
* `parameter.py`:  Parameter finding code for finding the optimal model parameters, e.g. learning rate, hidden layer size, regularization parameters.
* `test.py`: Model test code to output the final accuracy of model in test set.

## Dataset

- **VOC**: 

## Running training and evaluation

- Clone the repo: `git clone https://github.com/Lockegogo/FDU_HW/tree/main/DATA620004/HW1.git`
- [Download MNIST Dataset](https://pan.baidu.com/s/1YhCCpJtHg1COBNOl04Ky_Q?pwd=yvu5) (code: yvu5), unzip it  in  folder `./Datasets/MNIST`
- [Download the trained model](https://pan.baidu.com/s/1-lD76XyVP_6AMNSODHf7bA?pwd=k42h) (code: k42h), unzip it in folder `./Results`
- Select the best parameter: `python parameter.py`
- Get the accuracy of the best model in test set: `python test.py`









