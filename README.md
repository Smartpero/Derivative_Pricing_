# Derivative_Pricing_

## Description

This repository will contain projects, scripts, and notebooks related to **derivative pricing**.  
It is intended for implementing models such as Black-Scholes, binomial/trinomial trees, and Monte Carlo simulation for pricing financial derivatives (options, futures, swaps, etc.).

## Table of Contents

- [Installation](#installation)  
- [Usage](#usage)  
- [Features](#features)  
- [Configuration](#configuration)  
- [License](#license)  

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/Smartpero/Derivative_Pricing_.git
   cd Derivative_Pricing_
2. (Optional) Create a virtual environment:
   python3 -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
3. Install dependencies:
   pip install -r requirements.txt
   If requirements.txt is not yet created, you may install basic dependencies manually:
   pip install numpy scipy pandas matplotlib seaborn statsmodels
   
## Usage

Add Jupyter notebooks or scripts into this repository.

- Example workflow (future setup):
  python price_option.py --model black_scholes --S0 100 --K 105 --T 1 --r 0.05 --sigma 0.2
- Launch Jupyter for interactive exploration:
  jupyter notebook
## Features

- Black-Scholes pricing for European options

- Binomial and trinomial tree methods

- Monte Carlo simulation pricing

- Calculation of Greeks (Delta, Gamma, Vega, Theta, Rho)

- Visualization of payoffs, sensitivities, and convergence
## Configuration

- Model Parameters: strike price, volatility, interest rate, time to maturity, underlying price

- Computation Parameters: number of steps (trees), number of simulations, random seeds

- Data Paths: location of input data files (if using market data)

- Output Settings: figures, reports, or export directories

  Provide configuration files (e.g. config.json or .env) if needed for reproducibility.
  ## License

This project is licensed under the MIT License.




