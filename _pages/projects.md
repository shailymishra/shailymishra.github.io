---
layout: page
title: projects
permalink: /projects/
description: "Some projects that I have worked on in the past:"
nav: true
display_categories: [work, fun]
horizontal: false
---


##### machine learning   
* __Supervised Learning__ [[Code]](https://github.com/shailymishra/) 
    - Classified MNIST dataset using MAP, MLE, Bayesian pairwise, and perpendicular bisectors to understand the fundamentals of data and classification.
    - Classified Face using six different features (Eigen Face, Fisher Face, KernelPCA, Kernel Fisher Face, VGG Face, ResNet) by training MLP classifier on Yale Face, Indian Movie Face, and IIT-CFW Database and used t-SNE for face visualization. 
    - Implemented data dimensionality reduction using PCA and ISOMAP on the CIFAR-10 dataset and classified using SVM.
<!-- ___ -->

- __Unsupervised Learning__  [[Code]](https://github.com/shailymishra/)
    - Implemented Manifold learning methods - MDS, LLE, and ISOMAP. Performed k-means and spectral clustering on the Concentric Circles and Swiss roll dataset and visualized using manifold in 2-D. 
<!-- ___ -->

- __Reinforcement Learning__   [[Code]](https://github.com/shailymishra/) 
    - Formulated modified version of BlackJack and Walk-Tram Problem as MDP, and learned to play using Value Iteration and Q-Learning in Python.

- __Graph Neural Networks__   [[Code]](https://github.com/shailymishra/) 
    - Trained Graph Neural Network to perform Node Classification on CiteSeer dataset and Graph Classification on IMDB-BINARY dataset.
    - Trained Graph Convolutional Network to perform Node Clustering on CiteSeer dataset using PyTorch Geometric.

- __Fair Classifiers__   [[Code]](https://github.com/shailymishra/) 
    - Implemented AISTATS-17 paper in Python on fair classifiers (Logistic Regression and SVM) free from both disparate treatment and disparate impact. 

- __Optimization__  [[Code]](https://github.com/shailymishra/)
    - Solved Sudoku, Best Polyhedron, Largest Ball, and Jigsaw Puzzle as linear programming optimization in python. Solved fair and efficient allocations of indivisible goods and chores using Gurobi.

- __Sample Complexity__  [[pdf]](https://github.com/shailymishra/)
    - Explored and Created report on Generalization bounds and Sample Complexity covering VC dimension and Rademacher Averages with detailed proofs.

___

##### game theory  
- __Adx TAC__  [[Code]](https://github.com/shailymishra/)
    - Built an agent in a team of three to play a very simplified version of Ad Exchange(Adx) in Trading Agent Competition (TAC) in which agents needs to bid for ads such that they fulfill their campaigns in a efficient way.

- __Player Strategies__  [[Code]](https://github.com/shailymishra/)
    - Created a program in python to find strategies (mini-max, pure nash, mixed strategy) for a two-player zero-sum game (nfg file format). 

- __Paper Presentation__  [[ppt]](https://github.com/shailymishra/paperpresentations)
    - Presented various papers as given in the link.
    - Presented the EC'19 paper [Pacing Equilibrium in First-Price Auction Markets](https://dl.acm.org/doi/pdf/10.1145/3328526.3329600) in detail, uploaded on [Youtube](https://www.youtube.com/watch?v=2BqNnlWiY-c&ab_channel=AbhigyanGhosh) in a team of three.

- __Paper Implementation__  [[Link]](https://github.com/shailymishra/paperimplementations)
    - Implemented MoulinNet and RegretNet-nm of the IJCAI-18 paper on Deep Learning for Multi-Facility Location Mechanism Design using PyTorch.
    - Implemented RegretNet of the ICML-19 paper Optimal Auctions through Deep Learning using PyTorch
    - Implemented Automated Mechanism Design via Neural Networks.

___

##### game-theoretic fairness

- __Fair Room-Allocation  Rent Division Fairness__  [[pdf]](https://github.com/shailymishra/)
    - Analyzed game theoretic properties of fair rent division with and performed experiment using NYtimes rent and Spliddit. The goal is to fairly allocate rent and rooms to agents such that desirable properties like Envy-free, Efficient, Individual Rationality, and have non-negative Prices.

- __Fairness Algorithm__ [[Code]](https://github.com/shailymishra/)
    - Implemented popular fairness algorithms such as EF1, MNW, PE, CRR, Lipton Cycle Elimination, Generalized Adjusted Winner rule, etc.

- __Likelihood of fair and efficient allocation__ [[Code]](https://github.com/shailymishra/)
    - Conducted an empirical experiment on how likely it is to have fair and efficient allocations for validation drawn from different distributions. 

- __Fairness and Externalities__ [[Code]](https://github.com/shailymishra/)
    - Derived a connection between 2-D externalities in fairness to 1-D via utility transformation.
    - Proved the non-existence of alpha-MMS in 2-D externalities.

___

##### game-theoretic fairness + machine learning
- __EF1 fair allocation__ [[Code]](https://github.com/shailymishra/)
    -  Trained a neural network to learn EF1 fair allocation for indivisible items by formulating optimization problems as a lagrangian loss function.
    -  Solved the problem of learning non-integral allocations by using oscillating temperature parameters.
    - Implemented bagging to solve the problem of inefficient local minima to boost the network performance.
    - Trained the network for additive and general valuations.

- __EF1 + maximal USW allocation__ [[Code]](https://github.com/shailymishra/)
    - Designed a scalable fully convolution network inspired by UNET to learn EF1 and maximum welfare allocation for indivisible items (goods and chores) by optimization problems as a lagrangian loss function and improved the state-of-art.
    - Inferred the price of fairness based on empirical results.

___


##### blockchains
- __Decentrailized Application__  [[Code]](https://github.com/shailymishra/)
    - Created dAPP for two games (Battlefiled and Rock-paper-scissors-lizard-Spock) using MEAN framework, and solidity for smart contracts in team of two).

___

<!-- - __j__ 
[[Code]](https://github.com/HareeshBahuleyan/seizure-prediction-kaggle) <br>
  <p style="text-align:justify">EEG signals record electrical activity of the brain and can be used to predict the onset of a seizure. A competition conducted by the University of Melbourne on Kaggle required participants to classify 10-minute EEG clips into clips into either interictal or pre-ictal. I appoached the problem using an XGBoost classifier trained on (1) Time domain features, (2) Frequency domain features, and (3) EEG Specific Features. </p>

___

- __Text Classification using LSTMs__ 
[[Code]](https://github.com/HareeshBahuleyan/deeplearning-tutorials/tree/master/text-classification-lstm) <br>
  <p style="text-align:justify">Carry out a sentiment analysis task on the Rotten Tomatoes movie review dataset using recurrent neural networks. Specifically, an LSTM was trained with sentences (sequence of words) to predict the sentiment label.</p>

___

- __Airbnb Rental Price Prediction__ 
[[Code]](https://github.com/HareeshBahuleyan/airbnb-analysis) <br>
  <p style="text-align:justify">Python Selenium is used to scrape listings data from airbnb.ca for the city of Toronto. An extensive exploratory data analysis is carried out, following which, a price prediction model is built using information such as in-house amenitites and neighbourhood facilites as features.</p> -->

___