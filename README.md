# EWMA Variance Tracker: Real-Time Predictive Modeling and Automated Core-Tail Gaussian Mixtures for CrunchDAO

This notebook builds a threat-aware EWMA variance tracker using automated core-tail Gaussian mixtures for adaptive modeling. Developed for CrunchDAO’s market competition, it enables real-time uncertainty estimation and volatility-sensitive predictions.

## 🔍 Project Overview

This project implements a dynamic variance estimation framework using:
- **Exponentially Weighted Moving Average (EWMA)** for adaptive smoothing
- **Two-component Gaussian Mixture Model (GMM)** to separate core vs. tail behavior
- **Threat-aware weighting** to emphasize volatility spikes and rare events

The model is designed to support real-time signal generation in financial forecasting tasks, particularly in competitive environments like **CrunchDAO**.

## 📈 Key Features

- Real-time variance tracking using EWMA
- Core-tail Gaussian mixture modeling
- Adaptive threat scaling with FEWVar
- Visual diagnostics and synthetic data simulation
- Modular, reproducible notebook structure

## 🧠 Motivation

In high-stakes forecasting (e.g., financial markets), understanding **uncertainty** is as important as predicting the mean. This tracker helps:
- Detect regime shifts
- Quantify volatility bursts
- Improve model calibration and risk sensitivity

## 🛠️ Tech Stack

- Python 3.x
- NumPy, pandas, matplotlib
- Custom `birdgame` package for FEWVar
- Jupyter Notebook (Google Colab compatible)

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/GRP-AI/EWMA-Variance-Tracker.git
   cd EWMA-Variance-Tracker
