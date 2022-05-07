# SVM
Support Vector Machines (SVMs in short) are machine learning algorithms that are used for classification and regression purposes. SVMs are one of the powerful machine learning algorithms for classification, regression and outlier detection purposes. An SVM classifier builds a model that assigns new data points to one of the given categories. Thus, it can be viewed as a non-probabilistic binary linear classifier. The original SVM algorithm was developed by Vladimir N Vapnik and Alexey Ya. Chervonenkis in 1963. At that time, the algorithm was in early stages. The only possibility is to draw hyperplanes for linear classifier. In 1992, Bernhard E. Boser, Isabelle M Guyon and Vladimir N Vapnik suggested a way to create non-linear classifiers by applying the kernel trick to maximum-margin hyperplanes. The current standard was proposed by Corinna Cortes and Vapnik in 1993 and published in 1995. SVMs can be used for linear classification purposes. In addition to performing linear classification, SVMs can efficiently perform a non-linear classification using the kernel trick. It enable us to implicitly map the inputs into high dimensional feature spaces.

## Dataset
In this project, I will use Gender Classification Dataset from Kaggle
 - longhair: This column contains 0's and 1's where 1 is "long hair" and 0 is "not long hair".
 - foreheadwidthcm: This column is in CM's. This is the width of the forehead. 
 - foreheadheightcm: This is the height of the forehead and it's in Cm's.
 - nosewide: This column contains 0's and 1's where 1 is "wide nose" and 0 is "not wide nose". 
 - noselong: This column contains 0's and 1's where 1 is "Long nose" and 0 is "not long nose".
 - lipsthin: This column contains 0's and 1's where 1 represents the "thin lips" while 0 is "Not thin lips".
 - distancenosetoliplong: This column contains 0's and 1's where 1 represents the "long distance between nose and lips" while 0 is "short distance between nose and lips".
 - gender: This is either "Male" or "Female".

## Task
In this project, I will use SVM to find the classification on gender.
