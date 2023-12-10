### The code  EnvMultipleStock_validation is similar to EnvMultipleStock_train with some differences

# Turbulence Threshold:
- The StockEnvValidation class has an additional parameter turbulence_threshold compared to StockEnvTrain.
- This threshold is used to determine whether to take a different action strategy when the turbulence exceeds a certain level.

# Turbulence Handling in Actions:
- In the step method, if self.turbulence is greater than or equal to self.turbulence_threshold, all actions are set to sell (-HMAX_NORMALIZE).
- This means that during high turbulence, the agent is encouraged to sell stocks rather than making other buy/sell decisions.

# In summary, the StockEnvValidation class is adapted to handle turbulence, with a specific threshold, and encourages selling during high turbulence periods.
