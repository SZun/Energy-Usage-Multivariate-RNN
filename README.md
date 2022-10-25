# Tensorflow-Multivariate-RNN
A multivariate recurrent neural network using an appliance energy usage dataset

## [Notebook Here](https://github.com/SZun/Tensorflow-Multivariate-RNN/blob/main/Multivariate-RNN.ipynb)

## Images from Notebook

![](./assets/scaled.png)
![](./assets/model.png)
![](./assets/earlystop.png)
![](./assets/generator.png)
![](./assets/autocorrelation-2.png)
![](./assets/autocorrelation-1.png)
![](./assets/forecast-1.png)
![](./assets/forecast-2.png)

## Getting Started

### Prerequisites

You must have anaconda and conda installed

```
$ anaconda --version
```
*# OUTPUT: "anaconda Command line client (version 1.11.0)"*
```
$ conda --verison
```
*# OUTPUT: "conda 22.9.0"*


### Installing

**Clone** the repo using SSH

```
$ git clone git@github.com:SZun/Tensorflow-Multivariate-RNN
```

Then **cd** into the directory

```
$ cd Tensorflow-Multivariate-RNN
```

Create the environment, add it to jupyter and launch jupyter lab

```
$ conda env create -f tensorflow_env.yml
$ jupyter kernelspec remove ENVIRONMENT_1_NAME ENVIRONMENT_2_NAME
$ conda install -c conda-forge nb_conda_kernels -y
$ jupyter lab
```

## Built With

- [Tensorflow](https://www.tensorflow.org/)
- [Keras](https://keras.io/)
- [Scikit-Learn](https://scikit-learn.org/stable/)
- [Pandas](https://pandas.pydata.org/docs/#)
- [Numpy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/stable/index.html)

## Author

**Samuel Zun** 
- [LinkedIn](https://www.linkedin.com/in/szun/) | [Github](https://github.com/SZun)