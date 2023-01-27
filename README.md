# ECG200-dataset
## Analysing ECG200 time series dataset using Neural Network

The objective of this project is to explore the use of convolutional neural networks (CNNs) and recurrent neural networks (RNNs) for training electrocardiography (ECG) time series dataset - ECG200. 
These types of neural networks are particularly well-suited for analyzing sequential data, such as ECG time series, and have been used successfully in a variety of applications including natural language processing and speech recognition. 

By training a CNN or RNN on an ECG time series dataset, it is possible to learn complex patterns and relationships in the data and make predictions or detect anomalies. The use of CNNs and RNNs for training ECG time series datasets has the potential to improve the accuracy and efficiency of medical diagnosis and could lead to the development of new and more effective treatment strategies.


## Dataset

The dataset used in this project is ECG200 from the UCR archive. The ECG200 dataset was created as part of a thesis on ”Generalized feature extraction for structural pattern recognition in time-series data” by R. Olszewski at Carnegie Mellon University in 2001.

The ECG200 dataset is a collection of 200 electrocardiography (ECG) signals, which are recordings of the electrical activity of the heart. The signals in the dataset were collected from two different groups of individuals: those with normal heart function and those with myocardial heart disease (also known as coronary artery disease). Myocardial heart disease is a condition in which the coronary arteries, which supply blood and oxygen to the heart, become narrowed or blocked, leading to impaired heart function.

The ECG200 dataset is divided into two subgroups, each containing 100 signals. The first subgroup contains ECG signals from individuals with normal heart function, while the second subgroup contains ECG signals from individuals with myocardial heart disease. It consists of recordings of electrical activity during individual heartbeats, formatted for use in research on time-series data analysis. The ECG200 dataset is often used for research purposes, including the development of algorithms for the detection and classification of heart conditions. 

The ECG200 dataset is a collection of 200 electrocardiography (ECG) signals, each of which has 97 columns of data. The first column of data in each signal is the class label, which indicates whether the signal is from an individual with normal heart function (labeled as 1) or from an individual with myocardial heart disease (labeled as -1). The remaining 96 columns contain the time series data for the ECG signal. These columns represent the electrical activity of the heart over a period of time, with each column representing a specific time point. The ECG200 dataset is commonly used in research on ECG signal analysis and the detection and classification of heart conditions.