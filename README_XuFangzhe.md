# Requirements
Code tested on following environments:
* Windows 10
* python 3.8.8
* numpy 1.19.5
* matplotlib 3.3.4
* sklearn 0.24.1
* pytorch 1.8.1-cpu
* keras 2.4.3

# Train-Test Accuracy

Pytorch(Q5):  
    train:[44.2,74.3,87.8,91.6,93.3,94.3,95.0,95.4,95.8,96.2]  
    test: [63.6,85.1,91.5,93.4,94.4,95.2,95.7,96.0,96.3,96.6]

Keras(Q6):  
    train:[73.5,95.7,97.0,97.5,97.9,98.2,98.4,98.6,98.6,98.6]  
    test: [96.9,98.0,98.2,98.6,98.6,98.9,99.1,98.9,99.0,99.0]

Sklearn:  
    logistic regression(Q1):  
        train:[97.23]  
        test: [88.30]  
    naive_bayes(Q2):  
        train:[82.03]  
        test: [80.00]  
    SVM(Q3):  
        train:[97.70]  
        test: [86.00]  
    SVM_change_params(Q4):  
        train:[95.03]  
        test: [88.50]