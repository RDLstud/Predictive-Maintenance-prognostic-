# Predictive-Maintenance-RUL estimation-
This project explores the application of **deep learning models** to **time series data** from a simulated machine in order to estimate the **Remaining Useful Life (RUL)** of components. It was developed as part of a university course on temporal data analysis and health management in predictive maintenance systems.

---

## Objectives

- Understand the temporal evolution of sensor data in machinery.
- Predict the Remaining Useful Life (RUL) of a machine given time series inputs.
- Evaluate and compare deep learning models for prognostics.
- Experiment with early-stage **survival analysis** techniques.

---

## Dataset

- **Source**: Synthetic dataset generated from a machine simulation.
- **Description**: Multivariate time series with sensor readings over operational cycles.
- The dataset includes multiple units (machines), each with time-dependent degradation.

---

## Exploratory Data Analysis

A brief EDA was conducted to:
- Understand the nature of time series signals.
- Visualize feature behavior across time and detect **degradation patterns**.
- Identify **anomalous features** (without thresholding) that might signal changes in machine condition.

**Assumptions**:
- RUL was modeled as **linearly decreasing** from a maximum to zero, which is not fully realistic but acceptable for educational purposes.
- No hard thresholding was used to define anomalies in features.

---

## Modeling & Methodology

- Multiple models were trained to predict RUL based on sensor values.
- The RUL ground truth was explicitly modeled and added to the dataset.
> - Preliminary experiments in **survival analysis** were introduced (e.g., Cox-based or logistic hazard models).

---
