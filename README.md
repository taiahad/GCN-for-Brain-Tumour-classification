# GCN-for-Brain-Tumour-classification

## Overview

This repository contains the implementation of graph convolutional network (GCN)-based approaches for four-class brain tumour MRI classification.

Three models were developed:

1. Hybrid CNN-GCN framework
2. GCN with conventional feature extraction and graph construction
3. GCN without explicit graph construction

The proposed hybrid framework integrates:

- CNN-based deep feature extraction
- TensorFlow/scikit-learn preprocessing
- Feature normalization and dimensionality reduction
- Graph construction methods
- Graph Convolutional Networks (GCNs)

## Graph Construction Methods

The following graph-building strategies were investigated:

- k-Nearest Neighbour (kNN)
- Radial Basis Function (RBF)
- ε-Cosine graph
- Domain-specific graph

## Dataset

The framework was evaluated on a four-class brain tumour MRI dataset:

- Glioma
- Meningioma
- Pituitary tumour
- No tumour

The dataset is not included due to size and licensing restrictions.

## Requirements

Python environment:

- TensorFlow
- Keras
- scikit-learn
- Spektral
- NumPy
- SciPy

## Experiments

The repository includes Jupyter notebooks for:

- Hybrid CNN-GCN experiments
- Different graph construction methods
- Ablation studies
- Explainable AI analysis
- GCN comparison experiments

## Reproducibility

The provided notebooks contain:

- preprocessing steps
- feature extraction
- graph generation
- GCN training
- evaluation procedures
