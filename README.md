# Monte Carlo Simulation Program

This program performs a Monte Carlo simulation to generate multiple price paths for a financial asset over a given period of time, using a specified set of input parameters. The simulation is based on a geometric Brownian motion model, which assumes that the asset's price follows a lognormal distribution and is affected by a random drift and volatility.

-  # What is Monte Carlo Simulation?
Monte Carlo simulation is a technique used to model the probability of different outcomes in a process that cannot easily be predicted due to the presence of random variables. It is named after the famous Monte Carlo Casino in Monaco, where games of chance involve random events that cannot be accurately predicted. In finance, Monte Carlo simulations are often used to model the behavior of financial assets and estimate their value over time.

To learn more about Monte Carlo simulations and how they are used in finance, see these resources:
- "Monte Carlo Simulation" on Investopedia: https://www.investopedia.com/terms/m/montecarlosimulation.asp
- "Introduction to Monte Carlo Simulation" on Corporate Finance Institute: https://corporatefinanceinstitute.com/resources/knowledge/modeling/monte-carlo-simulation/
- "Monte Carlo Methods in Finance" by Peter Jäckel: https://www.cambridge.org/core/books/monte-carlo-methods-in-finance/910C9B9C5BEBE5A977D5F5C5B5C6941B

# Usage:
    `python monte_carlo_simulation.py`

# Input parameters:
    - num_simulations: Number of price paths to generate (default: 1000)
    - num_years: Number of years to simulate (default: 10)
    - initial_price: Initial price of the asset (default: 100)
    - mu: Annual drift rate (default: 0.05)
    - sigma: Annual volatility rate (default: 0.2)

# Output:
    A plot of the generated price paths over time.

# Example:
   ` python monte_carlo_simulation.py --num_simulations 5000 --num_years 5 --initial_price 50 --mu 0.03 --sigma 0.15`

# Dependencies:
    - NumPy
    - Matplotlib


