# Intro to Deep Learning

## Short Primer on Learning in Deep Learning

### Contents

* [Training Models](#Learning) [1]
    * [Linear Regression](#Linear-Regression)
        * [The Normal Equation](#Optimization-1:-The-Normal-Equation)
        * [Gradient Descent](#Optimization-2:-Gradient-Descent)
        
    * [Polynomial Regression](#Polynomial-Regression)
    
    * [Learning Curves](#Learning-Curves)
    
    * [Regularized Linear Models](#Regularized-Linear-Models)
        * [Ridge Regression](#Ridge-Regression-(Tikhonov-Regularization))
        * [Lasso Regression](#Lasso-Regression)
        * [Elastic Net](#Elastic-Net)
        * [Early Stopping](#Early-Stopping)
    
    * [Logistic Regression](#Logistic-Regression)
    
    * [Softmax Regression](#Softmax-Regression)

    * [The Perceptron](#The-Perceptron)

    * [Multi Layer Perceptron](#Multi-Layer-Perceptron) [2]

* [Artificial Neural Networks](#Artificial-Neural-Networks) [3]
    * [Backpropagation: Theory Behind, algorithm and implementation by Michael Nielsen](#Backpropagation)
    * [Improving The Way Neural Networks Learn](#Improving-The-Way-Neural-Networks-Learn)
    * [Vanishing Gradient Problem](#Vanishing-Gradient)
        
### References

[[1]](https://www.oreilly.com/library/view/hands-on-machine-learning/9781491962282/) Aurélien Géron, "Hands-On Machine Learning with Scikit-Learn and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems" (1st. ed.). O’Reilly Media, Inc.

[[2]](https://www.coursera.org/learn/machine-learning/home/week/5) Andrew Ng, Machine Learning MOOC, Neural Networks: Learning. Coursera

[[3]](http://neuralnetworksanddeeplearning.com/index.html) Michael A. Nielsen, "Neural Networks and Deep Learning (2015). Determination Press

### Deployment

#### Installation 

* pull the repo on local machine
```console
$ git clone https://github.com/antelk/lora-time-series.git
```

* [install Anaconda 2019.10](https://www.anaconda.com/distribution/)

* in cloned repo, activate Conda environment
```console
$ conda env create -f environement.yml -n learning
```

* start the environment 
```console
$ conda activate learning
```

* deactivate the environment (activate *base* environment)
```console
$ conda deactivate
```

#### Start the notebook

* in cloned repo, run jupyter
```console
$ jupyter notebook 
```
