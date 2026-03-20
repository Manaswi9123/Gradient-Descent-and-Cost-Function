# Gradient-Descent-and-Cost-Function
# 📉 Gradient Descent & Cost Function Optimization

This repository explores the fundamental optimization mathematics that power modern Machine Learning. It features a manual implementation of **Gradient Descent** to minimize the **Mean Squared Error (MSE)** and find the optimal parameters for a linear model.

---

## 🛠️ The Mathematical Stack
* **Python**: Core logic and algorithm implementation.
* **NumPy**: For efficient vectorization and matrix calculations.
* **Matplotlib**: To visualize the reduction in cost over iterations.

---

## 🧠 Concepts Implemented

### 1. The Cost Function (MSE)
To measure how "wrong" the model is, I implemented the Mean Squared Error formula:
$$MSE = \frac{1}{n} \sum_{i=1}^{n} (y_{actual} - y_{predicted})^2$$

### 2. Gradient Descent Algorithm
The model iteratively updates the weights ($m$) and bias ($b$) by calculating the partial derivatives of the cost function:
* **Learning Rate ($\alpha$):** Controlled the size of the steps taken toward the minimum.
* **Partial Derivatives:** Calculated the slope to determine the direction of the update.
* **Update Rule:** $$m = m - \alpha \frac{\partial J}{\partial m}$$
  $$b = b - \alpha \frac{\partial J}{\partial b}$$

### 3. Iterative Optimization
* Tracked the "Cost" at every iteration to ensure the algorithm was converging.
* Visualized the relationship between the number of iterations and the decrease in error.

---

## 📊 Key Insights
* **Convergence:** Demonstrated how the model eventually reaches a global minimum where the cost is minimized.
* **Learning Rate Impact:** Experimented with how different $\alpha$ values can lead to fast convergence or prevent the model from settling.

---

## 🚀 How to Run

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/Manaswi9123/Python-DataScience-Fundamentals.git](https://github.com/Manaswi9123/Python-DataScience-Fundamentals.git)
