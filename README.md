Quantitative Analysis: Option Pricing Models

This repository contains an implementation and comparison of three widely-used option pricing models: Black-Scholes, Binomial Model, and Monte Carlo Simulation.

Project Description

The objective of this project is to understand the underlying mathematics and assumptions of each model, implement these models in Python, and test their performance using historical options data.

Models Implemented

Black-Scholes Model - Assumes that financial markets are efficient, returns are normally distributed, and there's no arbitrage opportunity.
Binomial Option Pricing Model - Considers the possible paths the underlying asset's price can take, treating price changes as a binomial tree.
Monte Carlo Simulation - Simulates a large number of price paths and calculates the payoff for each path to estimate the option's price.
Data

The project uses historical options data, comparing the prices predicted by the models to actual market prices. The source of the data is Data Source Name. Note: Replace with actual source details.

Files Included

black_scholes.py: Python script containing the implementation of the Black-Scholes model.
binomial_model.py: Python script containing the implementation of the Binomial Option Pricing Model.
monte_carlo.py: Python script containing the implementation of the Monte Carlo Simulation.
data_processing.py: Python script used for cleaning and processing the historical data.
analysis.py: Python script used to analyze the results and compare the models.
data/: Folder containing the historical options data.
results/: Folder containing the results of the model simulations.
Requirements

This project requires Python and the following Python libraries installed:

NumPy
pandas
matplotlib
scipy
You will also need to have software installed to run and execute a Jupyter Notebook.

Run

To run the project:

Download the project or clone this repository.
Run the Python scripts in the order listed above, or open the Jupyter notebook and run the cells sequentially.
Results

The results and analysis of the project can be found in the analysis.py script and in the results/ directory.

