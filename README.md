# Solar Power Forecasting

This repository contains the research and implementation for the project: **"Research and evaluation of machine learning and deep learning models for short-term solar power forecasting."**

The project focuses on developing, training, and evaluating various models to predict solar power generation at multiple horizons (1-hour, 4-hour, and 24-hour) simultaneously.

## Project Overview

Accurate solar power forecasting is essential for grid stability and efficient energy management. This project investigates a diverse set of models, ranging from traditional machine learning to advanced deep learning architectures, to handle the inherent variability of solar energy.

### Models Implemented
The following models were implemented and compared:
- **Linear Regression (LR)**
- **XGBoost (XGB)**
- **Long Short-Term Memory (LSTM)**
- **Gated Recurrent Unit (GRU)**
- **CNN-LSTM**

### Forecasting Horizons
- 1-hour ahead (t+1)
- 4-hours ahead (t+4)
- 24-hours ahead (t+24)

## Dataset
This study utilizes the **DKASC Alice Springs** dataset, covering historical solar power generation data along with meteorological parameters.

## Repository Structure
- `solar_pipeline.ipynb`: The main Jupyter Notebook containing data preprocessing, model building, training, and evaluation pipelines.
- `README.md`: Project documentation.

## Requirements
To run the project, you need the following dependencies:
- Python 3.x
- pandas
- numpy
- scikit-learn
- tensorflow/keras (for Deep Learning models)
- xgboost
- pvlib

## License
This project is part of my Bachelor's Thesis at Hanoi University of Science and Technology.

---
*Author: Ong Hoang Thuy Ngoc*
