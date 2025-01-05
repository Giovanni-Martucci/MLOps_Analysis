# README

## Overview

This project focuses on analyzing customer data to segment them into meaningful clusters. The goal is to identify high-value customers and those who are price-sensitive, enabling tailored marketing strategies and product recommendations.

### Deliverables
- **Presentation**: The project’s summary and analysis steps are documented in `Bets_presentation.pdf`.
- **Code**: The entire implementation is available in the provided Jupyter notebook file (`.ipynb`).

## Installation Guide

Follow these steps to set up the environment:

1. **Create a Conda Environment**:
   ```bash
   conda create -n analytics python=3.10
   ```
2. **Activate the Environment**:
   ```bash
   conda activate analytics
   ```
3. **Install Required Dependencies**:
   Ensure you have the `requirements.txt` file in the project directory, then run:
   ```bash
   pip install -r requirements.txt
   ```

## File Descriptions

- **`Bet_presentation.pdf`**: Contains the presentation summarizing the problem statement, proposed solution, key steps, and results.
- **`test.ipynb`**: Jupyter Notebook with the full implementation, including data preprocessing, clustering, and model training.

## Running the Code

1. Launch Jupyter Notebook:
   ```bash
   jupyter-lab
   ```
2. Open the file `solution.ipynb` and execute the cells sequentially.

## Key Features

1. **Data Preprocessing**:
   - Handling missing values.
   - Creating new features.
   - Feature engineering with techniques like PCA and scaling.
2. **Clustering Analysis**:
   - Implementation of K-Means with optimal cluster selection using Elbow and Silhouette methods. Implementation of others supervied model.
3. **Real-Time Adaptation**:
   - Development of different strategies with PySpark and Integration with Feature Store for efficient feature management and low-latency predictions.

---
