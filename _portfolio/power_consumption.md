---
title: "Forecasting Household Power Consumption"
date: 2024-01-01
description: "A novel forecasting approach that combines neural nets with deterministic Fourier features to account for daily, weekly, and annual cycles in household power consumption."
github_url: "https://github.com/FraMaBu/forecast-power-consumption"
hero_image: "assets/images/power_hero.jpg"
categories: [Portfolio]
---
This project explores a new method for predicting household power consumption—an essential task for efficient energy management and grid optimization.

# Why is it important?
Accurate forecasting enables energy providers to anticipate demand, optimize grid operations, and deliver reliable service. By reducing forecasting errors, the hybrid model can lead to significant cost savings and a more efficient energy distribution system.

# How did we do it?
I implemented and compared three forecasting techniques:
- **Linear Regression:** A simple approach that assumes linear relationships.
- **LSTM Model:** A neural network that learns temporal dependencies.
- **Hybrid Model (LSTM + Fourier Features):** An advanced model that integrates deterministic Fourier features (encoding daily, weekly, and annual cycles) with an LSTM. This hybrid approach reduced Mean Squared Error by over 8% relative to the baseline.