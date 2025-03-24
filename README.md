# Black-Scholes-Julia
The goal is to present and explain the Black-Scholes Equation, and how one can solve it for various options.

Project map

black-scholes-project/
├── environment.yml                # For reproducibility
├── data/                          # Any market data you might use
├── src/                           # Julia modules for reusable code
│   ├── models/                    # Implementation of numerical methods
│   │   ├── finite_difference.jl
│   │   ├── monte_carlo.jl
│   │   ├── crank_nicolson.jl
│   │   └── pinns.jl
│   ├── visualization.jl           # Plotting utilities
│   └── utils.jl                   # Utility functions, logging, etc.
├── notebooks/                     # Jupyter notebooks
│   ├── 01_introduction.ipynb
│   ├── 02_binomial_to_bs.ipynb
│   ├── 03_stochastic_calculus.ipynb
│   ├── 04_bse_derivation.ipynb
│   ├── 05_numerical_methods.ipynb
│   └── 06_comparative_analysis.ipynb
└── README.md 

