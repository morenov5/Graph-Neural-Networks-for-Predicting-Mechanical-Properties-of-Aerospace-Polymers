# GNN-Based Elastic Modulus Prediction for Aerospace Polymers

This repository contains a Graph Neural Network (GNN) framework for predicting the elastic modulus of aerospace-relevant polymers under varying thermal and mechanical conditions. The model uses atom-level graph representations of synthetic polymer chains and conditions them on temperature and strain rate to estimate mechanical properties.

## Overview

- Materials modeled: Polyethylene (PE), Nylon 6, and Kevlar
- Approach: Graph Convolutional Networks (GCNs) with environmental conditioning
- Target property: Elastic modulus \(E\) (in GPa)
- Inputs: Atom features, molecular graph structure, temperature (°C), and strain rate (%/s)
- Output: Predicted elastic modulus under given conditions

## Installation

To run this project, you need Python ≥3.8 and the following libraries:

```bash
pip install torch torch-geometric scikit-learn matplotlib numpy
