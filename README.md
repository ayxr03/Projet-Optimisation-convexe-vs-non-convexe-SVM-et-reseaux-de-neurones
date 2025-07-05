# Binary Classification: SVM (SMO) vs. MLP (SGD & Adam)

[cite_start]This project explores and compares convex and non-convex optimization techniques in the context of binary classification[cite: 1]. The focus is on distinguishing digits '3' and '8' from the MNIST dataset using two primary approaches:
* [cite_start]Support Vector Machine (SVM) optimized using Sequential Minimal Optimization (SMO) [cite: 2]
* [cite_start]Multilayer Perceptron (MLP) trained with SGD and Adam optimizers [cite: 2]

## Dataset

* [cite_start]**Source:** MNIST dataset [cite: 2]
* **Preprocessing:**
    * [cite_start]Filtered to keep only digits 3 and 8 [cite: 2]
    * [cite_start]Flattened to 784-dimensional vectors [cite: 2]
    * [cite_start]Normalized pixel values [cite: 2]
    * [cite_start]Binary label encoding [cite: 2]
* **Split:**
    * [cite_start]80% Training/Validation [cite: 2]
    * [cite_start]20% Test [cite: 2]

## Models and Optimizers

### Support Vector Machine (SVM)
* [cite_start]Trained using SMO [cite: 2]

### Multilayer Perceptron (MLP)
* [cite_start]Tuned using Keras Tuner [cite: 2]
* Compared two optimizers:
    * [cite_start]Stochastic Gradient Descent (SGD) [cite: 2]
    * [cite_start]Adam [cite: 2]

## Evaluation Metrics

* [cite_start]Loss [cite: 2]
* [cite_start]Accuracy [cite: 2]
* [cite_start]Precision [cite: 2]
* [cite_start]Recall [cite: 2]
* [cite_start]F1-Score [cite: 2]
* [cite_start]ROC AUC [cite: 2]
* [cite_start]Training time [cite: 2]

## Key Results

| Model     | Test Accuracy | F1-Score | ROC AUC | Training Time |
| :-------- | :------------ | :------- | :------ | :------------ |
| SVM (SMO) | 99.40%        | 0.9938   | 0.9998  | 45.84 sec     |
| MLP (Adam)| 98.99%        | 0.9897   | 0.9992  | 28.21 sec     |
| MLP (SGD) | 99.19%        | 0.9918   | 0.9992  | 61.88 sec     |
[cite_start][cite: 3]

## Libraries

Main libraries used:
* [cite_start]`tensorflow` [cite: 4]
* [cite_start]`keras-tuner` [cite: 4]
* [cite_start]`scikit-learn` [cite: 4]
* [cite_start]`numpy` [cite: 4]
* [cite_start]`matplotlib` [cite: 4]
* [cite_start]`seaborn` [cite: 4]
* [cite_start]`pandas` [cite: 4]
