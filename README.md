# TFT Tutorial: Code and Application

This repository provides a step-by-step tutorial on the Temporal Fusion Transformer (TFT) for time series forecasting using PyTorch.

The project uses daily cryptocurrency data obtained from Yahoo Finance and includes a custom function designed to ensure full reproducibility of experimental results.

## Project Structure

- DATA_PREPARATION.ipynb: data collection and preprocessing pipeline
- TFT_TUTORIAL_GITHUB.ipynb: model implementation and training

## Data

The dataset consists of daily financial time series, including Bitcoin prices and macro-financial variables such as gold, oil, equity indices, and exchange rates. Data are downloaded directly using the `yfinance` library.

## Reproducibility

A custom function is implemented to ensure reproducibility of results by controlling random seeds across all relevant libraries.

## Requirements

Install dependencies with:

pip install -r requirements.txt
