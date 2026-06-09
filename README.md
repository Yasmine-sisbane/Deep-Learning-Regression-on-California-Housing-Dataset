
# California Housing Price Prediction using Deep Neural Networks

## Project Overview

This project applies Deep Learning techniques to predict housing prices using the California Housing dataset.

The project was developed using PyTorch and explores the impact of different neural network architectures and hyperparameters on regression performance.

## Dataset

The California Housing dataset contains information about housing districts in California, including:

* Median income
* House age
* Average number of rooms
* Average number of bedrooms
* Population
* Average occupancy
* Latitude
* Longitude

Target variable:

* Median House Value

## Project Structure

* `ex1_dataset.py` — Data loading, preprocessing, train/validation/test split.
* `ex2_model.py` — Deep Feed-Forward Neural Network implementation and training procedure.
* `ex4_grid_search.py` — Hyperparameter tuning using Grid Search.
* `ex5_random_search.py` — Hyperparameter tuning using Random Search.

## Technologies

* Python
* PyTorch
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

## Experiments

The project evaluates several hyperparameters:

* Network architectures
* Activation functions
* Learning rates
* Weight decay
* Dropout rates
* Gradient clipping values

Both Grid Search and Random Search are used to identify the best-performing configurations.

## Results

The best models achieved low validation Mean Squared Error (MSE) on the California Housing dataset, demonstrating the effectiveness of hyperparameter optimization for neural network regression tasks.

## Author

Yasmine Sisbane
Jihan Salek
Computer Science Student
