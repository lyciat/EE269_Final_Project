# EE269_Final_Project
Using ML and SP techniques to predict epileptic seizures and diagnose epilepsy from EEG signals

Modification 1: Transforms
1. No Transforms (original data)
2. Fourier Transform
3. Wavelet Transform


Modification 3: Classification Method
1. Linear SVM 
2. Polynomial SVM (degrees = 2, 3, 4, 5)
4. Multilayer Perceptron (100 layers, ReLU activation function, LR = 0.001)
5. k-Nearest Neighbors (k = 1, 2, ..., 10)

Polynomial SVM:

TIME:
[0.96695652 0.8726087  0.94782609 0.86434783]

FFT:
[0.9573913  0.86782609 0.94608696 0.86782609]

CWT:
[0.97347826 0.9726087  0.97130435 0.97086957]

Accuracy of Polynomial SVM with Time Data:  0.8726086956521739
Confusion Matrix of Polynomial SVM with Time Data:  [[1832    3]
 [ 290  175]]

Accuracy of Polynomial SVM with FFT Data:  0.8678260869565217
Confusion Matrix of Polynomial SVM with FFT Data:  [[1834    1]
 [ 303  162]]

Accuracy of Polynomial SVM with CWT Data:  0.9726086956521739
Confusion Matrix of Polynomial SVM with CWT Data:  [[1826    9]
 [  54  411]]

Linear SVM:

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


Accuracy of k-Nearest Neighbor Classifier:
Time:
[0.94869565 0.92130435 0.9326087  0.91869565 0.92478261 0.9173913
 0.92043478 0.91608696 0.91913043 0.91478261]

FFT:
[0.93782609 0.92173913 0.93217391 0.91869565 0.9273913  0.92173913
 0.92565217 0.92086957 0.9226087  0.91826087]

 CWT:
[0.97173913 0.96086957 0.96826087 0.96434783 0.96782609 0.9626087
 0.96434783 0.96130435 0.96478261 0.9626087 ]

**Total Experiments using Linear SVM:**
1. No Transforms, No Feature Selection, SVM (done)
2. Fourier Transform, No Feature Selection, SVM (done)
3. Wavelet Transform, No Feature Selection, SVM (done)


**Total Experiments using Multilevel Perceptron:**
1. No Transforms, No Feature Selection, Multilayer Perceptron (done)
2. Fourier Transform, No Feature Selection, Multilayer Perceptron (done)
3. Wavelet Transform, No Feature Selection, Multilayer Perceptron (done)

**Total Experiments using k-Nearest Neighbors:**
1. No Transforms, No Feature Selection, k-Nearest Neighbors (done)
2. Fourier Transform, No Feature Selection, k-Nearest Neighbors (done)
3. Wavelet Transform, No Feature Selection, k-Nearest Neighbors (done)
