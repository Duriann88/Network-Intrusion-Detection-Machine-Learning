# Network-Intrusion-Detection-Machine-Learning
The goal of this project is to develop a machine learning-based model to simulate the classification of network connections as either benign or malicious. Using a supervised learning approach, the model will be trained on a labelled dataset with features like protocol type, service, flag, byte counts, and connection rates, the model will predict whether a given network connection represents an attack (Yes/1) or not (No/0). Key attributes such as connection duration, protocol type, and error rates will be used to train and evaluate the model. This simulation aims to provide insights into how these features can be leveraged for network traffic classification, helping to model potential real-world attack detection scenarios.

This project is focused on simulating the enhancement of Intrusion Prevention Systems (IPS) and Intrusion Detection Systems (IDS) by incorporating an automated detection mechanism using machine learning algorithms. The performance of the model will be evaluated through accuracy, precision, recall, and F1-score metrics, ensuring that it effectively identifies attacks while minimising false positives and negatives. To better communicate the thought process that went into the project, sections titled ‘Rationale’ are included. By simulating attack detection, the project aims to explore how machine learning can be applied to improve the detection of malicious traffic in real-world network security systems. The results of this simulation could contribute to better automated threat detection frameworks in the future.


**Problem Statement**
How can we design a robust automated intrusion detection system that leverages machine learning techniques, such as logistic regression and random tree, to effectively classify network traffic as benign or malicious by analysing key factors like traffic characteristics, packet behaviors, attack signatures, and statistical patterns from both network connections and destination hosts?


**Data sourced:**
Smart Home Intrusion Detection Dataset by Jacob
https://www.kaggle.com/datasets/bobaaayoung/dataset-invade
