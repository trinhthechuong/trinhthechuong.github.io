---
title: "Synergy of advanced machine learning and deep neural networks with consensus molecular docking for virtual screening of anaplastic lymphoma kinase inhibitors"
collection: publications
permalink: /publication/SR_ALK
excerpt: 'This study addresses the urgent need for an AI model to predict Anaplastic Lymphoma Kinase (ALK) inhibitors for Non-Small Cell Lung Cancer treatment, targeting the ALK-positive mutation...'
date: 2025-01-20
venue: 'Journal of Computer-Aided Molecular Design'
paperurl: 'https://link.springer.com/article/10.1007/s10822-025-00657-6'
citation: 'Trinh, T.C., et al. Synergy of advanced machine learning and deep neural networks with consensus molecular docking for virtual screening of anaplastic lymphoma kinase inhibitors. J Comput Aided Mol Des 39, 7 (2025). https://doi.org/10.1007/s10822-025-00657-6'
---


**Abstract**: 
This study addresses the urgent need for an AI model to predict Anaplastic Lymphoma Kinase (ALK) inhibitors for Non-Small Cell Lung Cancer treatment, targeting the ALK-positive mutation. With only five Food and Drug Administration approved ALK inhibitors currently available, effective drugs remain in demand. Leveraging machine learning (ML) and deep learning (DL), our research accelerates the precise screening of novel ALK inhibitors using both ligand-based and structure-based approaches. In ligand-based approach, an ensemble voting model comprising three base learners to classify potential ALK inhibitors, achieving promising retrospective validation results. Notably, the ML-based XGBoost algorithm exhibited compelling results with external validation (EV)-f1 score of 0.921, EV-Average Precision (AP) of 0.961, cross-validation (CV)-f1 score of 0.888±0.039 and CV-AP of 0.939±0.032. Besides, the DL-based Artificial Neural Network (ANN) model demonstrated comparative performance with EV-f1 score of 0.930, EV-AP of 0.955, CV-f1 score of 0.891±0.037 and CV-AP of 0.934±0.040. For structure-based approach, an XGBoost consensus docking model utilized scores from three molecular docking programs (GNINA 1.0, Vina-GPU 2.0, and AutoDock-GPU) as features. Combining these two approaches, we virtually screened 120,571 compounds, identifying three promising ALK inhibitors, CHEMBL1689515, CHEMBL2380351, and CHEMBL102714, that bind to the protein’s pocket and establish hydrophobic contacts in the hinge region through their ketone groups, resembling Alectinib’s interaction. Comparative analysis revealed traditional ML models outperformed Graph Neural Networks (GNN), highlighting the critical role of feature engineering and dataset size importance. The study recommends further in vitro testing to validate the prospective screening performance of these models. 

**Keywords:** *ALK, XGBoost, Artificial Neural Network, Graph Neural Network, Molecular Docking, Consensus Docking.*

[Link to paper](https://link.springer.com/article/10.1007/s10822-025-00657-6)

[Link Github code](https://github.com/trinhthechuong/ML-ANN-GNN-for-Screening-potential-iALKs)
