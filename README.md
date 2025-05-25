# Stellar Classification and Visualization

This project focuses on classifying celestial objects into three categories: **GALAXY**, **QSO**, and **STAR**, based on their photometric data and redshift values.

## 🌌 Problem Statement
The goal is to develop a machine learning-based pipeline to classify stars, galaxies, and quasars from the SDSS dataset and visualize key data patterns for interpretability.

## 🔍 Key Features
- Data preprocessing: handling outliers and encoding categorical variables.
- Visualization: four types of visual analytics generated via `matplotlib` and `seaborn`.
- Classification report and confusion matrix visualization.
- Redshift distribution with trend fitting.
- Plate and class distributions using histograms and bar plots.

## 🧠 Model & Evaluation
- Classification metrics such as precision, recall, f1-score.
- Confusion matrix for performance breakdown.
- Synthetic data used in this version for visualization demo.

## 📊 Outputs
- Composite visualization saved as `stellar_analysis_report.png`.

## 🚀 Potential Improvements
- Integrate actual trained model predictions.
- Enhance UI/UX using interactive visualization (e.g., Plotly).
- Expand redshift and plate analysis with real-world data insights.

## 🗃️ Files
- `visualizer.py`: Contains the `StellarVisualizer` class with all visualization logic.
- `star_classification.csv`: Raw dataset used for processing and analysis.

## 🧑‍💻 Author
Developed for CS 422 - Spring 2025 by [Your Name].

