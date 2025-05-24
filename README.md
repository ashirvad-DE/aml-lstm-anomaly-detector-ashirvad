# AML LSTM Anomaly Detector

This project uses an LSTM Autoencoder to detect anomalous financial transactions for Anti-Money Laundering (AML) purposes.

## Project Structure

- `data/` - Contains dataset files.
- `notebooks/` - Jupyter notebooks for exploration, modeling, and evaluation.
- `models/` - Saved LSTM model weights.
- `utils/` - Helper scripts and functions.

## Setup Instructions

```bash
pip install -r requirements.txt
```

## Dataset

You can use:
- PaySim: https://github.com/EdgarSantosA/paySim
- Credit Card Fraud Dataset: https://www.kaggle.com/mlg-ulb/creditcardfraud

## Run the Notebooks

Start with:
- `notebooks/01_data_exploration.ipynb`
- `notebooks/02_model_training.ipynb`
