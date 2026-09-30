# ai-sales-forecasting-supply-chain
AI-powered sales forecasting and supply-chain simulation dashboard using NeuralProphet, Prophet and Auto-ARIMA.

# AI-Powered Sales Forecasting & Supply-Chain Simulation

## Overview

An end-to-end AI-powered demand forecasting and supply-chain simulation dashboard designed to help businesses forecast future demand and identify potential operational bottlenecks under demand surges.

## Problem Statement

Businesses often need to forecast future sales while simultaneously understanding whether their supply-chain infrastructure can handle sudden increases in demand.

This project combines AI-based forecasting with supply-chain stress testing to provide both demand predictions and operational insights.

## Key Features

- CSV-based sales data upload
- Automatic date and value-column detection
- Data cleaning and resampling
- Automatic frequency detection
- AI-based model selection
- 12-period demand forecasting
- 95% prediction intervals
- Rolling-origin backtesting
- MAPE and RMSE evaluation
- Supply-chain stress testing
- Inventory capacity analysis
- Warehouse capacity analysis
- Supplier lead-time analysis
- Last-mile delivery analysis
- Interactive dashboard

## AI/ML Models

The forecasting pipeline uses:

- NeuralProphet
- Prophet
- Auto-ARIMA

Model selection is based on dataset characteristics such as dataset length and seasonality.

## Technology Stack

- Python
- Pandas
- NeuralProphet
- Prophet
- Auto-ARIMA
- React
- TailwindCSS
- Recharts
- REST API
- Docker

## System Architecture

1. Data Upload
2. Data Cleaning & Preprocessing
3. Frequency Detection
4. Forecasting Model Selection
5. Forecast Generation
6. Backtesting & Evaluation
7. Supply-Chain Stress Testing
8. Interactive Visualization

## Supply-Chain Simulation

The project includes a demand-surge scenario where monthly orders are assumed to increase significantly.

The simulation evaluates:

- Inventory availability
- Warehouse throughput
- Supplier lead times
- Last-mile delivery
- Stockout risk

## Model Evaluation

Forecasting performance is evaluated using:

- MAPE
- RMSE
- Rolling-origin backtesting

## Results

The system provides:

- Future demand forecasts
- Prediction intervals
- Forecast performance metrics
- Supply-chain bottleneck identification
- Operational risk indicators

## Project Structure

```text
├── src/
├── data/
├── notebooks/
├── dashboard/
├── screenshots/
├── requirements.txt
└── README.md
