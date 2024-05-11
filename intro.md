# Parkinson Level Detection

Parkinson Diseases Level Detection

The aim of this project is to implement a system that is able to detect the Parkinson's level of patients with Parkinson's disease through their speech impairment. Four levels of Parkinson's based on the Unified Parkinson's Disease Rating Scale (UPDRS) are considered.

The system receives an audio signal, extracts its amplitude signal, then uses a feature extraction method for audio signals, which builds either a predictor matrix (tabular data) or a tensor (sequential data) by a classifier appropriate for each type of data.

Throughout the project, a multitude of alternatives are evaluated at two levels:

- Model level: a multitude of classifiers are tested, such as Random Forest, Multi-Layer Perceptron, XGBoost, Recurrent Neural Networks, among others.

- Feature extraction level: more than 250 feature extraction methods are considered, based on eight base methods and four types of statistics. 

A methodology is implemented to select the best alternative (pipeline) of all those explored, which will be used by the system.

The estimated future accuracy for the best alternative is 85%.

Further exploration of sequence-based models, such as Convolutional Neural Networks and better implementations of Recurrent Neural Networks, remains a possible task to improve the results of the system.

```{tableofcontents}
```
