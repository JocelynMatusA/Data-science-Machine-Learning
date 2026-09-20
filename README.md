# Data Science & Machine Learning Portfolio \ (^-^) /

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

Data science and machine learning projects covering data analysis, preprocessing, visualization, supervised, unsupervised, and reinforcement learning, dimensionality reduction, clustering, neural networks, CNNs, and Big Data technologies.

## Table of Contents
- [Overview](#overview)
- [Topics Covered](#topics-covered)
- [Tools and Technologies](#tools-and-technologies)
- [Repository Structure](#repository-structure)
- [Learning Outcomes](#learning-outcomes)
- [License](#license)
- [About](#about)

## Overview
This repository contains a collection of practical projects and exercises developed as part of my learning journey in data science and machine learning. The projects cover the full data science workflow — from statistical analysis and statistical inference, through data preprocessing and exploratory data analysis, to machine learning, deep learning, and Big Data applications.
## Research
- **Safe RL + control for energy system under cyberattacks** — co-authored manuscript *(in preparation, target: IOP Publishing)*
A comparative study of model-free reinforcement learning controllers (PPO, DDPG, TD3) applied to a nonlinear cyber-physical system under coordinated cyberattacks (Denial-of-Service, False Data Injection). Proposes RL-tuned PID and RL-supervised Model Predictive Control architectures, evaluated across 10 reward formulations with formal Lyapunov-based stability guarantees. Co-authors: Jocelyn Matus Ancavil, Guillermo Zieballe, Lautaro Salazar, Hugo O. Garcés — Universidad de Concepción, Chile.

## Topics Covered

### Statistical Analysis & Inference
- Descriptive statistics
- Probability distributions
- Hypothesis testing
- Confidence intervals
- Statistical inference
- Correlation analysis

### Data Analysis & Preprocessing
- Data acquisition from CSV, Excel, and web sources
- Data cleaning and missing value imputation
- Outlier detection and filtering
- Data wrangling (sorting, deduplication, sampling)
- Grouping, pivoting, and merging datasets
- Feature engineering
- Data normalization, encoding, and standardization

### Exploratory Data Analysis
- Univariate and multivariate analysis
- Descriptive statistics and measures of central tendency/dispersion
- Correlation analysis (Pearson's r and Spearman)
- Simple and multiple linear regression (statsmodels)
- Data visualization with Seaborn and Matplotlib
- Outlier analysis

### Supervised Learning
- Regression algorithms (Linear Regression)
- Classification algorithms (Logistic Regression, K-Nearest Neighbors, Decision Trees, Random Forest, SVM, Gradient Boosting)
- Data preprocessing and encoding (label/one-hot encoding, scaling)
- Cross-validation and bias-variance trade-off
- Hyperparameter tuning
- Performance metrics 

### Unsupervised Learning
- K-Means Clustering
- Hierarchical Clustering
- DBSCAN
- Cluster evaluation (elbow method, silhouette score)
- Principal Component Analysis (PCA)
- t-SNE
- Dimensionality reduction

### Reinforcement Learning
- Core RL concepts: policies, reward functions, exploration vs. exploitation, delayed reward
- Actor-Critic algorithms: PPO, DDPG, TD3
- RL for control systems: RL-tuned PID and RL-supervised Model Predictive Control (MPC)
- Reward function design and reward shaping (linear, exponential, Lyapunov-based, safety-constrained formulations)
- Safe reinforcement learning (Lagrangian- and barrier-based constraints)
- Stability analysis: Lyapunov consistency and uniformly ultimately bounded (UUB) convergence
- Applications in cyber-physical systems: resilience against cyberattacks (Denial-of-Service, False Data Injection)

### Deep Learning
- Artificial Neural Networks and the perceptron
- Fully Connected (dense) networks
- Activation functions, loss functions, and backpropagation
- Convolutional Neural Networks (CNNs) for image recognition
- Regularization (dropout) and hyperparameter tuning (learning rate, epochs)
- Model training and evaluation
- Frameworks: TensorFlow, Keras, PyTorch

### Big Data
- Distributed data processing
- In-memory processing
- Apache Spark
- Big Data concepts

## Tools and Technologies
- Python
- MATLAB
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Apache Spark
- Jupyter Notebook
- Visual Studio Code

## Repository Structure
```text
data-science-Machine-Learning/
│
├── 01-statistical-inference/
├── 02-data-exploration/
    ├── 06.videojuegos.csv
    └── data-exploration-seaborn-matplotlib-eda.ipynb
├── 03-data-preprocessing/
├── 04-supervised-learning/
├── 05-unsupervised-learning/
├── 06-dimensionality-reduction/
├── 07-clustering/
├── 08-reinforcement-learning/
├── 09-neural-networks/
├── 10-convolutional-neural-networks/
    └── CNN_explicación.pdf
├── 11-big-data/
├── P1-final-ipynb(en proceso)
│
└── README.md
```

## Learning Outcomes
Through these projects, I developed practical experience in:
- Applying statistical methods to analyze and interpret data.
- Performing statistical inference and hypothesis testing.
- Preparing and analyzing real-world datasets.
- Selecting and applying appropriate machine learning algorithms.
- Evaluating model performance using appropriate metrics, cross-validation, and k-fold.
- Applying dimensionality reduction and clustering techniques.
- Developing and evaluating neural network and convolutional neural network models.
- Understanding distributed data processing and Big Data technologies.
- Implementing reproducible data science workflows using Python.

## License
This project is licensed under the MIT License — feel free to use it for learning purposes with attribution.

## About
This repository represents my practical work and learning process in Statistical Inference, Data Science, Machine Learning, Deep Learning, and Big Data.
