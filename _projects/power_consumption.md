---
layout: project
title: "Forecasting Household Power Consumption with Hybrid LSTM-Fourier Model"
date: 2024-01-01
description: "A novel forecasting method that combines LSTM networks with Fourier features to account for daily, weekly, and annual cycles in household power consumption."
tags: [forecasting, power consumption, LSTM, Fourier, machine learning]
github: "https://github.com/FraMaBu/power-consumption-forecasting"
blog: "/blog/power-consumption-forecasting"
---

## What is the project?

This project explores a new method for predicting household power consumption—an essential task for efficient energy management and grid optimization.

## Why is it important?

Accurate forecasting enables energy providers to anticipate demand, optimize grid operations, and deliver reliable service. By reducing forecasting errors, the hybrid model can lead to significant cost savings and a more efficient energy distribution system.

## How did we do it?

I implemented and compared three forecasting techniques:
- **Linear Regression:** A simple approach that assumes linear relationships.
- **LSTM Model:** A neural network that learns temporal dependencies.
- **Hybrid Model (LSTM + Fourier Features):** An advanced model that integrates deterministic Fourier features (encoding daily, weekly, and annual cycles) with an LSTM. This hybrid approach reduced Mean Squared Error by over 8% relative to the baseline.

*(For more details, please see the accompanying blog article.)*