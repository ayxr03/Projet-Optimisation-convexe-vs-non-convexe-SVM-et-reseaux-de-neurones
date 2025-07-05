Binary Classification: SVM (SMO) vs. MLP (SGD & Adam)
This project explores and compares convex and non-convex optimization techniques in the context of binary classification. The focus is on distinguishing digits 3 and 8 from the MNIST dataset using two approaches:
•	Support Vector Machine (SVM) optimized using Sequential Minimal Optimization (SMO)
•	Multilayer Perceptron (MLP) trained with SGD and Adam optimizers
Dataset
•	Source: MNIST dataset
•	Preprocessing:
o	Filtered to keep only digits 3 and 8
o	Flattened to 784-dimensional vectors
o	Normalized pixel values
o	Binary label encoding
•	Split:
o	80% Training/Validation
o	20% Test

Models and Optimizers
Support Vector Machine (SVM)
•	Trained using SMO
Multilayer Perceptron (MLP)
•	Tuned using Keras Tuner 
•	Compared two optimizers:
o	Stochastic Gradient Descent (SGD) 
o	Adam
Evaluation Metrics
•	Loss
•	Accuracy
•	Precision
•	Recall
•	F1-Score
•	ROC AUC
•	Training time

Key Results
Model	Test Accuracy	F1-Score	ROC AUC	Training Time
SVM (SMO)	99.40%	0.9938	0.9998	45.84 sec
MLP (Adam)	98.99%	0.9897	0.9992	28.21 sec
MLP (SGD)	99.19%	0.9918	0.9992	61.88 sec

Libraries
Main libraries used:
•	tensorflow
•	keras-tuner
•	scikit-learn
•	numpy, matplotlib, seaborn, pandas

