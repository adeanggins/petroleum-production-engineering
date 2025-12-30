# Petroleum Production Engineering: A Python Approach

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## 📖 Overview
This repository contains a Python implementation of the workflows and calculations presented in the textbook **"Petroleum Production Engineering: A Computer-Assisted Approach"** by Boyun Guo and Ali Ghalambor.

Originally designed for Excel spreadsheets, these engineering workflows have been refactored into modular Python scripts and Jupyter Notebooks to allow for:
* **Scalability:** Process thousands of wells instead of one.
* **Optimization:** Use advanced solvers (Scipy) instead of manual goal-seeking.
* **Visualization:** Generate publication-quality plots using Matplotlib/Seaborn.

## 📂 Repository Structure

| Module | Description | Book Chapter |
| :--- | :--- | :--- |
| **`fluids`** | PVT correlations for Oil, Gas, and Water properties. | Ch. 2 |
| **`inflow`** | Reservoir Deliverability (IPR) for vertical and horizontal wells. | Ch. 3 |
| **`outflow`** | Wellbore performance (TPR) and multiphase flow correlations. | Ch. 4 |
| **`nodal`** | System analysis (Intersection of IPR and TPR). | Ch. 4 |
| **`lift`** | Artificial Lift design (Gas Lift, ESP, Sucker Rod). | Part III |

## 🚀 Getting Started

### Prerequisites
* Python 3.8+
* Jupyter Notebook
