Emmanuel G. Peregrino

Import numpy as np
From scipy.optimize import minimize
# Generate synthetic data
Np.random.seed(0)
X = np.linspace(0, 10, 50)
True_slope = 2.0
True_intercept = 1.0
Y = true_slope * X + true_intercept + np.random.randn(50)

# Define the linear regression model
Def linear_regression(params, X, y):
    Alpha, beta = params
    Y_pred = alpha + beta * X
    Error = y_pred – y
    Return np.sum(error**2)  # Sum of squared errors as loss function

# Initial guess for parameters (alpha, beta)
Initial_guess = [0, 0]

# Use scipy.optimize to find optimal parameters
Result = minimize(linear_regression, initial_guess, args=(X, y))

# Extract optimal parameters
Alpha_opt, beta_opt = result.x

# Print the estimated parameters
Print(“Estimated Intercept (alpha):”, alpha_opt)
Print(“Estimated Slope (beta):”, beta_opt)
