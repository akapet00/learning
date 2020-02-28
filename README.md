# Intro to Deep Learning

## Short Primer on Learning in Deep Learning

### Contents

* Training Models [1]
    * Linear Regression
        * The Normal Equation
        * Gradient Descent
        
    * Polynomial Regression
    
    * Learning Curves
    
    * Regularized Linear Models
        * Ridge Regression
        * Lasso Regression
        * Elastic Net
        * Early Stopping
    
    * Logistic Regression
    
    * Softmax Regression

    * The Perceptron

    * Multi Layer Perceptron [2]

* Artificial Neural Networks [3]
    * Backpropagation: Theory Behind, algorithm and implementation by Michael Nielsen
    * Improving The Way Neural Networks Learn
    * Vanishing Gradient Problem
        
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
