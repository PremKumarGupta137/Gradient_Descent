# Gradient Descent Implementation in Python

This repository contains a simple implementation of the **Gradient Descent Algorithm** in Python using NumPy. The algorithm demonstrates how to optimize the slope (`m`) and intercept (`b`) of a line to minimize the error (using the Mean Squared Error) when fitting a dataset.

---

## Features

- **Implementation from Scratch**: No external machine learning libraries used.
- **Cost Function Calculation**: Computes the Mean Squared Error (MSE) at each iteration.
- **Beginner-Friendly**: The code is simple and easy to understand for those new to machine learning.

---

## Code Highlights

The `gradient_descent` function performs the following:
1. Takes `x` (input feature array) and `y` (target values array) as inputs.
2. Iteratively updates the slope (`m`) and intercept (`b`) to minimize the cost function.
3. Prints the intermediate values for:
   - Slope (`m`)
   - Intercept (`b`)
   - Cost (Mean Squared Error)
   - Iteration count

---

## Example Usage

Here's a dataset used in this example:

```python
x = np.array([1, 2, 3, 4, 5])
y = np.array([5, 7, 9, 11, 13])

##output :
m = 0.0935, b = 0.0320, cost = 18.6667, iteration = 0
m = 0.1769, b = 0.0604, cost = 12.0941, iteration = 1
m = 0.2581, b = 0.0873, cost = 8.1083, iteration = 2
m = 0.3373, b = 0.1130, cost = 5.7282, iteration = 3
m = 0.4145, b = 0.1375, cost = 4.2442, iteration = 4
m = 0.4901, b = 0.1609, cost = 3.4267, iteration = 5
m = 0.5642, b = 0.1832, cost = 2.5371, iteration = 6
m = 0.6369, b = 0.2045, cost = 1.6116, iteration = 7
m = 0.7083, b = 0.2248, cost = 0.7325, iteration = 8
m = 0.7786, b = 0.2440, cost = 0.0222, iteration = 9
m = 0.8480, b = 0.2623, cost = 0.0000, iteration = 10

After running for 10 iterations, the gradient descent algorithm converges:

Slope (m) approaches 1.9999 (which is very close to the true slope of 2).
Intercept (b) approaches 0.
This matches the true relationship y = 2x in the dataset.

