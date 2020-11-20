
# ECS 289G Deep Learning - Final Project
Title: Deep Neural Networks for Drugs Classification Based on Biological Activity

Group members: Zekun Chen (zkuchen@ucdavis.edu), Giuseppe Barbalinardo (gbarbalinardo@ucdavis.edu), Yiming Wu (scywu@ucdavis.edu), Chenghan Sun (chesun@ucdavis.edu)

## Project Description

This project aims to facilitate new drug development, improving the Mechanism of Action (MoA) prediction algorithms. The MoA is a property of a drug, which helps to identify a protein target associated with disease and develop a molecule to modulate that protein target. Improving algorithms to predict such property can advance drug development by classifying drugs based on their biological activity.
We plan to achieve this goal with advanced machine learning algorithms, focusing on a deep learning neural network architecture (DNN) to address this course's topic. We propose to employ a state-of-the-art deep learning model, the Neural Oblivious Decision Ensembles (NODE), which has shown to be able to outperform alternative Gradient Boosting Decision Trees methods (GBDT) on tabular data to solve this kind of problems [1].
The data set for this project comes from an ongoing Kaggle competition [2], which consists of drugs in a pool of 100 different cell types, in addition to MoA annotations for more than 5,000 drugs. The given dataset features include gene expression, cell viability, treatments of cells, and the hours the cell has gone through the treatments. After developing our model, we will evaluate its performance on the average value of the logarithm loss function applied to each drug-MoA annotation pair.
The significance of this work resides in the improvement of the algorithm to determine the MoAs of a new drug and highlight the capability of using a universal framework for deep learning on tabular data.
Since drugs can have multiple MoA annotations, the task is formally a multi-label classification problem. We will present our well-trained DNN classifier, which automatically labels each case in the test set as one or more MoA classes, and eventually achieve a competitive advantage over the other machine learning approaches.

## References
[1] S. Popov, A. Babenko, S. Morozov - Neural Oblivious Decision Ensembles for Deep Learning on Tabular Data. arxiv/1909.06312
[2] Mechanisms of Action (MoA) Prediction - kaggle.com/c/lish-moa
    
