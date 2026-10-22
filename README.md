# Privacy Auditing in Centralized and Federated Learning

### Evaluating Privacy–Utility Trade-offs with Membership Inference Attacks

This repository contains the implementation of my Master's thesis conducted at **Luleå University of Technology (LTU)** in collaboration with **RISE Research Institutes of Sweden**.

## Research Objectives

- Evaluate privacy leakage in centralized and federated learning.
- Investigate membership inference attacks.
- Compare IID and Non-IID federated learning.
- Evaluate differential privacy mechanisms.

## Methodology

### 1. Centralized Machine Learning

The following models were implemented:

- Multilayer Perceptron (MLP)
- Random Forest (RF)
- XGBoost

#### Membership Inference Attacks

- Loss-based MIA
- Likelihood Ratio Attack (LiRA)

#### Privacy Defenses

- DP-SGD for MLP
- Laplace input perturbation for XGBoost

### 2. Federated Learning

Federated learning experiments were conducted under:

- **IID:** Independent and Identically Distributed
- **Non-IID:** Non-Independent and Identically Distributed

#### Membership Inference Attacks

- FedMIA-I: Loss-based attack
- FedMIA-II: Gradient-based attack using cosine similarity

## Dataset

**eICU Collaborative Research Database (eICU-CRD v2.0)**

Source: [PhysioNet](https://physionet.org/content/eicu-crd/2.0/)

The dataset is not included in this repository due to access restrictions.

## Technologies

- Python
- PyTorch
- Scikit-learn
- XGBoost
- Opacus
- Jupyter Notebook

## Author

**Fatima Juairiah**

M.Sc. in Data Science  
Luleå University of Technology, Sweden

**ORCID:** [0009-0000-9576-908X](https://orcid.org/0009-0000-9576-908X)

## Acknowledgments

This research was conducted at Luleå University of Technology in collaboration with RISE Research Institutes of Sweden.
