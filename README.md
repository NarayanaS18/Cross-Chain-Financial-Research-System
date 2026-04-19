# Cross-Chain Financial Research System

An ML-powered framework to analyze, compare, and predict trends across stock and cryptocurrency markets.

## Overview

Financial markets are fast-moving and data-rich. This project provides tools and notebook workflows to:

- Ingest and harmonize cross-chain market data (stocks & crypto)
- Preprocess and engineer features for ML
- Train and evaluate predictive models for trend detection
- Visualize results and export predictions

## Highlights

- Cross-asset analysis: compare signals across markets
- Reproducible Jupyter notebook pipeline
- Model training, evaluation, and prediction outputs
- Lightweight structure ready for expansion (APIs, dashboards)

## Project Structure

 - [mlf final.ipynb](mlf final.ipynb) — Main analysis notebook
 - [README.md](README.md) — Project documentation
 - requirement.txt - contains the requirement

## Quick Start

1. Clone the repository

```
git clone https://github.com/NarayanaS18/Cross-Chain-Financial-Research-System.git
cd Cross-Chain-Financial-Research-System
```

2. Create and activate a Python virtual environment (recommended)

Windows

```
python -m venv venv
venv\\Scripts\\activate
```

macOS / Linux

```
python -m venv venv
source venv/bin/activate
```

3. Install dependencies

```
pip install -r requirements.txt
```

If `requirements.txt` is not provided, install the commonly used packages manually:

```
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

4. Launch Jupyter and open the notebook

```
jupyter notebook
```

Open the notebook: [mlf final.ipynb](mlf final.ipynb)

## Usage (Notebook Flow)

Run the notebook cells sequentially to reproduce the pipeline:

1. Data loading and inspection
2. Data cleaning and preprocessing
3. Feature engineering and scaling
4. Model training and validation
5. Evaluation, visualization, and exporting predictions

## Features & Techniques

- Cross-chain data handling (stocks + crypto)
- Exploratory data analysis and visualizations
- Supervised ML models (regression/classification)
- Time series methods (optional, where applicable)
- Metrics: accuracy, RMSE, precision/recall, AUC (as relevant)

## Outputs

- Trained model files in `models/`
- Plots and reports in `outputs/`
- CSV/JSON prediction exports

## Recommended Improvements

- Add automated data ingestion (APIs / cron jobs)
- Add advanced sequence models (LSTM/Transformer) for time series
- Build a lightweight dashboard for live visualization


