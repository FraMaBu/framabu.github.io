---
title: "Forecasting Household Power Consumption"
date: 2025-02-10
excerpt: "A novel forecasting method for household power consumption that integrates neural networks with Fourier features to effectively model power consumption cycles."
header:
  overlay_image: "/assets/images/power_hero.png"
  overlay_filter: 0.5
  caption: "Photo credit: DALL-E 3"
  teaser: "/assets/images/power_hero.png"
  actions:
    - label: "View Repository"
      url: "https://github.com/FraMaBu/forecast-power-consumption"

---
This project explores a new method for predicting household power consumption—an essential task for efficient energy management and grid optimization.

# Why is it important?
Accurate forecasting enables energy providers to anticipate demand, optimize grid operations, and deliver reliable service. By reducing forecasting errors, the hybrid model can lead to significant cost savings and a more efficient energy distribution system.

# How did we do it?
I implemented and compared three forecasting techniques:
- **Linear Regression:** A simple approach that assumes linear relationships.
- **LSTM Model:** A neural network that learns temporal dependencies.
- **Hybrid Model (LSTM + Fourier Features):** An advanced model that integrates deterministic Fourier features (encoding daily, weekly, and annual cycles) with an LSTM. This hybrid approach reduced Mean Squared Error by over 8% relative to the baseline.