# Farming Optimization Using Reinforcement Learning, Time-Series Analysis, and Multi-Objective Optimization

## Overview

This project aims to optimize farming operations by leveraging Reinforcement Learning (RL), Time-Series Analysis, and Multi-Objective Optimization. The goal is to automate decision-making, predict plant growth, and balance competing objectives such as maximizing crop yield while minimizing resource usage (e.g., water, energy).

### Dataset

The dataset used in this project includes time-series data from farming sensors, such as:

- Temperature (Layer A and Layer B)
- Humidity (Layer A and Layer B)
- Door State (open/closed)
- Timestamp (for time-based analysis)

The dataset was preprocessed to:

- Remove units and convert columns to numeric values.
- Handle missing values.
- Create additional features (e.g., rolling averages, time-based features).

### Code Structure

1. Data Preprocessing
2. Reinforcement Learning
3. Time-Series Analysis
4. Multi-Objective Optimization

### Results

1. Reinforcement Learning:
- The RL agent learns to make decisions that optimize farming operations.
- Training logs and the trained model are saved for future use.

2. Time-Series Analysis:
- The model provides accurate predictions of plant growth and resource needs.
- Evaluation metrics (e.g., MSE) are reported.

3. Multi-Objective Optimization:
- The optimal solution balances competing objectives, providing actionable recommendations for farming operations.

### Source

https://www.kaggle.com/datasets/midouazerty/work-for-parmavir
