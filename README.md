
---

# 3D Fireball Particle Simulation & Advanced Data Science Analysis

This repository contains a comprehensive Python project that simulates a 3D fireball particle distribution and applies advanced data science techniques to analyze, model, and visualize the data.

---

## Project Overview

* **Simulation**: Generates 5,000 particles arranged in a spherical fireball shape with intensity decreasing from the center outward.
* **Dimensionality Reduction**: Applies PCA and t-SNE to visualize and understand particle distribution and cluster structures.
* **Clustering**: Uses K-Means to identify natural clusters within the particles.
* **Machine Learning Models**:

  * **Regression**: Random Forest Regressor predicts particle intensity based on 3D coordinates.
  * **Classification**: Random Forest Classifier predicts particle cluster assignments.
* **Hyperparameter Tuning**: Employs GridSearchCV to optimize model parameters for better performance.
* **Model Explainability**: Utilizes Partial Dependence Plots and SHAP values to interpret model predictions.
* **Interactive Visualizations**: Creates dynamic 3D plots with Plotly for intuitive data exploration.
* **Model Persistence**: Saves trained models for future use or deployment.

---

## Installation

Use the following commands to set up your environment:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn plotly shap joblib
```

---

## Usage

1. **Run the complete simulation and analysis** in a Jupyter notebook or Google Colab environment by executing the main script.

2. The workflow includes:

   * Generating particle data with coordinates and intensity
   * Performing PCA and clustering
   * Training and tuning Random Forest models for regression and classification
   * Visualizing results with static and interactive plots
   * Interpreting model predictions using SHAP and Partial Dependence Plots

3. **Interactive plots** can be explored in Jupyter notebooks or Google Colab.

---

## Features

* 3D particle simulation using spherical coordinates
* Dimensionality reduction via PCA and t-SNE
* Cluster analysis with K-Means
* Random Forest modeling with hyperparameter tuning
* Model interpretation with SHAP and Partial Dependence Plots
* Interactive 3D visualizations using Plotly
* Model saving/loading for production readiness

---

## Visuals

![Image Alt](https://github.com/tajulislamsaidul/Fireball_DataScience_Report.pdf/blob/d6b2789da947d7961ab0aedb11309a3fdc84f4a2/Fireball_DataScience_Report.gif)

---

## Contributing

Contributions and improvements are welcome! Feel free to open issues or submit pull requests.
🔥 Let’s light up data science with fireball insights! 🔥

---
