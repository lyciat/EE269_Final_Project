# EE269_Final_Project
Using ML and SP techniques to predict epileptic seizures and diagnose epilepsy from EEG signals

Modification 1: Transforms
1. No Transforms (original data)
2. Fourier Transform
3. Wavelet Transform

Modification 2: Feature Selection
1. Feature Selection (PCA)
2. No Feature Selection

Modification 3: Classification Method
1. SVM
2. Multilayer Perceptron

SVM:

Accuracy of Linear SVM on Time Series Data: 0.84

Confusion Matrix:
 [[1826    9]
 [ 359  106]]

Accuracy of Linear SVM on FFT Data: 0.6239130434782608

Confusion Matrix:
 [[1216  619]
 [ 246  219]]

 
Accuracy of Linear SVM on CWT Data: 0.8891304347826087

Confusion Matrix:
 [[1808   27]
 [ 228  237]]


MLP:

Accuracy of MLP Classifier on timeseries Data: 0.86

Confusion Matrix:
 [[1612  223]
 [  99  366]]

Accuracy of MLP Classifier on FFT Data: 0.8773913043478261

Confusion Matrix:
 [[1663  172]
 [ 110  355]]
 
Accuracy of MLP Classifier on CWT Data: 0.9721739130434782

Confusion Matrix:
 [[1802   33]
 [  31  434]]


**Total Experiments using SVM:**
1. No Transforms, No Feature Selection, SVM (done)
2. No Transforms, Feature Selection, SVM
3. Fourier Transform, No Feature Selection, SVM (done)
4. Fourier Transform, Feature Selection, SVM
5. Wavelet Transform, No Feature Selection, SVM (done)
6. Wavelet Transform, Feature Selection, SVM

**Total Experiments using Multilevel Perceptron:**
1. No Transforms, No Feature Selection, Multilayer Perceptron (done)
2. No Transforms, Feature Selection, Multilayer Perceptron
3. Fourier Transform, No Feature Selection, Multilayer Perceptron (done)
4. Fourier Transform, Feature Selection, Multilayer Perceptron
5. Wavelet Transform, No Feature Selection, Multilayer Perceptron (done)
6. Wavelet Transform, Feature Selection, Multilayer Perceptron
