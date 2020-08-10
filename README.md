# touch-gesture-cnn

Presented is a deep convolutional neural network algorithm aimed at correctly classifying social
touch gestures. Time series are transformed to the visual domain to infer correlations among
the multivariate dynamics of the signal. By means of transfer learning, the Xception model is
implemented paired with 2 additional higher level layers. The model is trained on the Corpus of Social Touch (CoST)
dataset. A within-subject design using 10-fold cross-validation for model selecting and a test 
set for evaluation, resulted in an accuracy of 61.5%.


# dataset

The Corpus of Social Touch (CoST) can be downloaded from https://doi.org/10.4121/uuid:5ef62345-3b3e-479c-8e1d-c922748c9b29 .
Using the files in '/R files' , the downloaded .xls file can be filtered in seperate files for each user and touch gesture.
