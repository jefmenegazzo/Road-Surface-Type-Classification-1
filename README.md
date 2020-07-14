# Road Surface Type Classification Based on Inertial Sensors and Machine Learning: A Comparison Between Classical and Deep Machine Learning Approaches For Multi-Contextual Real-world Scenarios

This project contains the Artificial Intelligence models and experiments developed for the paper [Road Surface Type Classification Based on Inertial Sensors and Machine Learning](). In this research, we developed models for the road surface type classification, classifying between segments of dirt, cobblestone and alphalt roads. We applied classical techniques of K-Means Clustering (KMC), Support Vector Machine (SVM) and K-Nearest Neighbors (KNN); and Deep Learning techniques based on Convolutional Neural Network (CNN), Long Short-Term Memory Network (LSTM) and hybrid LSTM-CNN. We analyzed in the time domain the data collected near and below the suspension in contextual variations, in addition to the impact of the data window. The contents of each folder are described below.

## Article

Click [here]() to access the article.

## Notebooks

The jupyter notebooks present in the folders correspond to the applied techniques. To run the models, just change the folders where the datasets are located (*datasets_folder*) and the work folder that has the experiments (*work_folder*).  These parameters are in the files **Classical Methods - Processing.ipynb** and **Deep Learning - Processing.ipynb files**. Other instructions are documented in source code.

## Experiments

This folder contains all the experiments performed. Each folder stores the experiments of a technique, among the generated models and execution logs.