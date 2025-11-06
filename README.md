# Finance-Models-in-Python 

## 1 The Black Scholes Model 

The Black-Scholes Model is a differential equation that estimates the theoretical value of financial derivatives, particularly European call and put options. 
It was developed by Fischer Black and Myron Scholes (and later contributed to by Robert Merton) and is a cornerstone of modern financial theory.The formula calculates the option's value by discounting the expected payoff at expiration back to the present, using a risk-neutral framework.

### Key Inputs (The "Five Variables"):

**1. Current Price of the Underlying Asset ($S$)**: The current stock or asset price.

**2 Option Strike Price ($K$)**:  The price at which the option holder can buy (call) or sell (put) the asset.

**3 Time to Expiration ($T$)**:  The time remaining until the option expires (in years).

**4 Risk-Free Interest Rate ($r$)**: The return on a risk-free investment (like a government bond) over the option's life, used for discounting.

**5.Volatility ($\sigma$)**: A measure of the underlying asset's price fluctuation, expressed as the standard deviation of its returns. This is the only input that is not directly observable.

### Limitations and Assumptions:
The original model relies on several simplifying assumptions, such as:The option is European-style (can only be exercised at expiration).
Volatility and the risk-free rate are constant over the option's life.No dividends are paid on the underlying asset (though the model has been adapted to include them).Markets are frictionless (no transaction costs or taxes).
