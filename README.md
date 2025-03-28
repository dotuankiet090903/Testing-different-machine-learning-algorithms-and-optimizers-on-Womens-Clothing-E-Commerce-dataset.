# Optimize Machine Learning algorithms on /Womens Clothing E-Commerce dataset

## Overview & Brief Description
Optimization algorithms play a crucial role in machine learning, directly impacting model performance, training efficiency, and convergence speed. This project aims to compare three widely used optimization techniques—Gradient Descent (GD), Stochastic Gradient Descent (SGD), and Adam (Adaptive Moment Estimation)—to analyze their differences in terms of computational efficiency, learning behavior, and overall effectiveness in minimizing loss functions.

Gradient Descent (GD) provides stable convergence by computing the gradient using the entire dataset but can be computationally expensive for large-scale problems. Stochastic Gradient Descent (SGD) improves efficiency by updating parameters using individual data points, making it more scalable but introducing variance in optimization. Adam, an adaptive learning algorithm, enhances SGD by incorporating momentum and per-parameter learning rates, offering faster and more reliable convergence in complex and noisy environments.

This project will implement and visualize these optimization methods using PyTorch and Matplotlib, showcasing their performance on a simple quadratic function. By comparing their optimization paths, memory usage, and response to noisy gradients, i aim to provide insights into selecting the most suitable algorithm for different machine learning tasks. Additionally, i will explore Continual Learning, which enables models to adapt to new data over time without forgetting previous knowledge, making it essential for real-world applications such as autonomous systems, recommendation engines, and fraud detection.

Through this comparative analysis, i seek to understand the strengths and trade-offs of each optimization method and their implications for various machine learning scenarios.

## Usage
Run file Algorithms and optimizers testing.ipynb
