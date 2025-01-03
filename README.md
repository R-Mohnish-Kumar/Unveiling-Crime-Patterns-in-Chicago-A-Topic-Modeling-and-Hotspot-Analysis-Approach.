# Unveiling Crime Patterns in Chicago: A Topic Modeling and Hotspot Analysis Approach

This project explores crime patterns in Chicago using topic modeling and hotspot analysis. By leveraging machine learning algorithms and visualization techniques, the project aims to provide actionable insights for law enforcement and city planning.

---

## Project Overview

1. **Dataset**: Chicago crime data with over 8 million rows, reduced to 100,000 rows for analysis. The dataset was downloaded from the [Chicago Data Portal](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2/about_data).
2. **Objectives**:
   - Extract latent patterns in crime types using Latent Dirichlet Allocation (LDA).
   - Detect and visualize crime hotspots using spatial clustering.
3. **Methods**:
   - **Topic Modeling**: Identifies dominant crime topics using LDA.
   - **Hotspot Detection**: Combines CatBoost, Gaussian Mixture Models, and Isolation Forest for risk analysis.

---

## Key Features

- **Exploratory Data Analysis**:
  - Univariate, bivariate analysis of crime distributions.
  - Temporal crime trends and spatial visualizations.
- **Topic Modeling**:
  - Text preprocessing (stopword removal, lemmatization).
  - Hyperparameter tuning for improved coherence.
  - Extraction of top crime-related themes.
- **Hotspot Analysis**:
  - Classification of crime-prone regions using supervised learning.
  - Clustering crime data spatially.
  - Ensemble prediction of risk levels.
- **Interactive Visualizations**:
  - Risk hotspots and crime clusters displayed on a map.
  - Heatmaps and scatter plots for pattern identification.

---

## Algorithms

- **Algorithms**:
  - Latent Dirichlet Allocation (LDA)
  - CatBoost Classifier
  - Gaussian Mixture Models (GMM)
  - Isolation Forest
  
---

## Installation and Usage

1. 1. Clone the repository:
   ```bash
   git clone https://github.com/username/repo-name.git
   cd repo-name
   ```
2. Open the Jupyter Notebook file:
   ```bash
   jupyter notebook unveiling_crime_patterns_in_chicago.ipynb
   ```
3. Execute the cells step-by-step to analyze the data and generate visualizations.
4. Explore outputs:
   - Visualize hotspots: `chicago_crime_map.html`
   - Analyze topics and clusters within the notebook.

---

## Results

1. **Topic Modeling**:
   - Coherence Score: `0.6591`
   - Identified key crime categories.
2. **Hotspot Analysis**:
   - Interactive map with crime clusters.
   - Highlighted high-risk zones for intervention.

---

## Future Work

- Incorporate temporal crime prediction.
- Add additional demographic features for deeper insights.
- Improve model efficiency for larger datasets.

---
