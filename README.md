# Pricing an Asian Call Option: Monte Carlo vs. PDE Approach
___


We explore two approaches to pricing an Asian option based on the arithmetic average of the underlying asset. The first uses Monte Carlo simulation under the risk-neutral measure, while the second provides a numerical solution to a partial differential equation derived through a Change-of-Numeráire argument. By comparing the discounted option values obtained from both methods at t=0, we demonstrate their consistency, analyze the computational trade-offs between stochastic and deterministic techniques, and highlight how the PDE formulation serves as a reliable benchmark for validating Monte Carlo pricing results.

Here is a sample of GBM paths used for the Monte Carlo simulation:

!([https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png](https://github.com/jfelipeosorio/asian_options/blob/main/output.png) "Logo Title Text 1")


To run the notebook just install the required packages `numpy,matplotlib,pandas,seaborn` in a Python environment.
