The project is divided into three main sections:

### 1. Asian Options

This folder focuses on pricing Asian options

-   `Euler_Pricer.ipynb`: Implements the Euler scheme to simulate asset paths and price the Asian option.
-   `Runge_Kutta_Pricer.ipynb`: Uses a Runge-Kutta (RK) scheme for a more accurate path simulation and option pricing.
-   `Standard_Pricer_MC.ipynb`: Contains a basic Monte Carlo simulation for pricing Asian options, serving as a benchmark.

### 2. European Option

This folder contains scripts for pricing a standard European call option.

-   `MLMC_Scheme_Pricer.ipynb`: Prices the option using the Multilevel Monte Carlo (MLMC) method, contains all schemes in a single script.
-   `Standard_Pricer_MC.ipynb`: Implements a Monte Carlo simulation to price the European option as a simple benchmark.

### 3. Heston Model

This implements the Heston stochastic volatility model, where the volatility of the asset is a random process itself.

-   `MLMC_Euler_Milstein_Pricer.ipynb`: Prices a European call option under the Heston model using the Milstein and Euler scheme.
