# [Federated Learning For Classifying Network Intrusions](https://github.com/athapa11/federated-nids-2022/blob/main/B922168_22COD290_2.pdf)
The repository contains my thesis project which focuses on implementing a federated learning framework [Flower](https://flower.dev/), using virtual clients to classify various network intrusions for Network Intrusion Detection Systems (NIDS). The objective is to explore the feasibility of multiple federated learning strategies, namely FedAvg, FedProx, and FedAdagrad.

# Abstract
The thesis offers a comprehensive investigation into the strengths and weaknesses of federated learning, a decentralised approach to machine learning. It focuses on the feasibility and effectiveness of various federated learning
strategies as an alternative to traditional machine learning methods, with a special emphasis on their application in classifying network intrusions. This is achieved by leveraging the distributed and heterogeneous data generated
by Internet of Things (IoT) devices. Although centralised learning demonstrated marginally superior overall accuracy, federated learning proved to be more effective in identifying a wider range of network intrusions, especially
within minority classes. Among the examined federated learning strategies, FedAvg delivered superior performance with feature selection, whereas FedProx showed strength when all features were considered. Challenges encountered included memory constraints posed by the use of virtual clients.

# Overview
The code has been developed in Python on Google Colab as a Jupyter Notebook file. The dataset used to conduct this research can be found [here](https://www.kaggle.com/datasets/ymirsky/network-attack-dataset-kitsune).

The following libraries were used:
 * flwr
 * math
 * NumPy
 * pandas
 * concurrent.futures (Optional - to parallelise tasks)
 * sklearn (Scikit-learn)
 * imblearn (Imbalance-learn)
 * fast_ml
 * torch
 * torchvision
 * collections
 * typing
 * matplotlib
 * seaborn
