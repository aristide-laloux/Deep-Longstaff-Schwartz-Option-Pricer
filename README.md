# Deep Longstaff Schwartz Bermudan Put Pricer

This project implements the Longstaff-Schwartz algorithm to price a Bermudan put option within the Black-Scholes model. The focus is on approximating the continuation function using different regression techniques.

## Notebooks

- **Notebook 1: Linear Regression Implementation**
  - Implements the Longstaff-Schwartz algorithm using linear regression to approximate the continuation function.

- **Notebook 2: Polynomial and Neural Network Regression**
  - Explores replacing the linear regression with a polynomial regression of varying ranks (from 1 to 50) to assess the effect on pricing accuracy.
  - Substitutes the linear regression with a neural network for further improvement in approximating the continuation function.
  - Conducts a study on overfitting by analyzing how increasing the polynomial rank affects the performance and pricing accuracy.
 
- **Notebook 3-4: Same computation for a Bermudan Call Option**
  - We apply the same algorithm and tests for the Bermudan Call Option.
  - We show that the American Call is indeed equal to the European Call when the dividend are zero and interest rates are positive.
 



