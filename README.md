# Petroleum Production Engineering: A Computer-Assisted Approach (Python)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Complete-success)

## 📖 Overview
This repository contains a Python implementation of the engineering workflows presented in the textbook **"Petroleum Production Engineering: A Computer-Assisted Approach"** by Boyun Guo and Ali Ghalambor.

Moving beyond the book's original Excel-based approach, this project utilizes Python's scientific stack (`scipy`, `numpy`, `matplotlib`) to build robust, scalable solvers for the entire well lifecycle—from reservoir fluid characterization to artificial lift design.

## 📂 Repository Structure

### 1. Core Modules
The library is organized by physical domain, covering 10 key chapters of the book:

| Description | Book Ch. |
| :--- | :--- |
| PVT correlations ($P_b$, $B_o$, $\mu$, $Z$-factor) using Standing & Beggs-Robinson. | Ch. 2 |
| Reservoir deliverability (Vogel, Fetkovich, Darcy) for IPR construction. | Ch. 3 |
| Wellbore gradient calculations (Hydrostatic + Friction) for TPR curves. | Ch. 4 |
| Choke performance models (Gilbert, Ros, Achong) and critical flow checks. | Ch. 5 |
| **Nodal Analysis Solver**: Finds the intersection of IPR and TPR to predict rates. | Ch. 6 |
| Production forecasting using **Arps' Decline Curve Analysis (DCA)**. | Ch. 7 |
| Root cause analysis (Skin vs. Tubing restriction) using model matching. | Ch. 8 |
| **Sucker Rod Pump** design: PPRL, MPRL, and Dynagraph generation. | Ch. 9 |
| **Gas Lift** design: IPO valve spacing and injection pressure optimization. | Ch. 10 |
| **ESP** design: Pump curve digitization, TDH calculation, and staging. | Ch. 11 |
| Matrix Acidizing ($P_{max}$) and Hydraulic Fracturing (**PKN Model**) design. | Ch. 12-13|

### 2. Notebooks (`notebooks/`)
Interactive step-by-step exercises for each chapter:
* `01_Fluid_Properties.ipynb`
* `02_Inflow_Performance.ipynb`
* `03_Wellbore_Performance.ipynb`
* `04_Nodal_Analysis_Solver.ipynb`
* `05_Artificial_Lift_GasLift.ipynb`
* `06_Choke_Performance.ipynb`
* `07_Well_Deliverability.ipynb`
* `08_Production_Forecast.ipynb`
* `09_Production_Diagnosis.ipynb`
* `10_Sucker_Rod_Pumping.ipynb`
* `11_Gas_Lift_Design.ipynb`
* `12_ESP_Design.ipynb`
* `13_Matrix_Acidizing.ipynb`
* `14_Hydraulic_Fracturing.ipynb`

### 3. Capstone Project
**`Capstone_End_To_End_Project.ipynb`**
A comprehensive, integrated simulation of a single well ("Well Omega-1") throughout its entire 10-year lifecycle:
1.  **Discovery:** Characterizing fluids.
2.  **Completion:** Designing a Hydraulic Frac job for tight rock.
3.  **Flow:** Sizing tubing and choke for natural flow.
4.  **Decline:** Forecasting revenue.
5.  **Damage:** Diagnosing skin damage vs. tubing scale.
6.  **Workover:** Designing an Acid job.
7.  **Revival:** Installing Gas Lift for late-life production.

## 🚀 Getting Started

### Prerequisites
* Python 3.8+
* `pip`
