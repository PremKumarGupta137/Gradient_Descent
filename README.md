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
x = np.array([1, 2, 3])
y = np.array([2, 4, 6])

## understanding

When running the algorithm, the gradient descent converges to:

Slope (m): ~2
Intercept (b): ~0
This fits the line y = 2x perfectly.|

##output :
m = 0.0935, b = 0.0320, cost = 18.6667, iteration = 0
m = 0.1769, b = 0.0604, cost = 12.0941, iteration = 1
...
m = 2.0000, b = 0.0000, cost = 0.0000, iteration = 999
