# L1 and L2 Regularization

**L1 and L2 Regularization** are techniques used in machine learning to prevent overfitting by penalizing model complexity. They add a regularization term to the loss function, which constrains the model's weights.

---

## What is Regularization?

Regularization is a method that helps improve the generalization of a model by discouraging it from fitting too closely to the training data. This is done by adding a penalty term to the model’s loss function.

### Key Concepts:

1. **Overfitting**: When a model learns noise and details from the training data, resulting in poor performance on new, unseen data.
2. **Loss Function**: A function that measures the error between the predicted and actual values.
3. **Weights/Parameters**: The coefficients that the model learns during training, which are used to make predictions.

---

## Types of Regularization:

### 1. L1 Regularization (Lasso)

- **Definition**: L1 regularization adds the sum of the absolute values of the model coefficients to the loss function. It leads to sparse solutions, where some of the model coefficients become zero, effectively selecting only the most important features.
  
  **L1 Regularization Term**:
  `'L1 penalty = λ Σ |w_i|'`
  
- **Application**: Useful when you want feature selection along with regularization. L1 regularization forces irrelevant or less important feature weights to become exactly zero.

### 2. L2 Regularization (Ridge)

- **Definition**: L2 regularization adds the sum of the squared values of the model coefficients to the loss function. It penalizes large weights more than small weights, helping to prevent overfitting.
  
  **L2 Regularization Term**:
  `'L2 penalty = λ Σ w_i^2'`
  
- **Application**: Helps control the complexity of the model by shrinking the weights but does not eliminate features as L1 does. It is useful when you want to keep all the features but reduce the impact of outliers or large weights.

---

## Differences Between L1 and L2 Regularization

| Aspect               | L1 Regularization                  | L2 Regularization                  |
|----------------------|------------------------------------|------------------------------------|
| Penalty               | Sum of absolute values of weights  | Sum of squared values of weights   |
| Feature Selection     | Can result in sparse models        | Keeps all features                 |
| Weight Shrinkage      | Can shrink some weights to zero    | Shrinks all weights uniformly      |
| Use Cases             | Feature selection                 | Preventing multicollinearity       |

---

## Why Regularization is Important

1. **Prevents Overfitting**: By penalizing large weights, regularization helps models generalize better to unseen data.
2. **Improves Model Simplicity**: Regularization reduces model complexity, making it more interpretable.
3. **Feature Selection (L1)**: L1 regularization performs feature selection by zeroing out less important feature weights.

---

## Practical Applications

- **L1 Regularization**: Commonly used in **sparse models**, such as Lasso Regression, where you want to select a subset of important features.
- **L2 Regularization**: Often used in models like **Ridge Regression** and **Logistic Regression**, where you aim to reduce overfitting without eliminating any features.

---

## Conclusion

L1 and L2 regularization are powerful techniques to control overfitting in machine learning models. By adding penalties to large coefficients, these methods ensure that the model remains simple and generalizes well to new data. L1 regularization is useful for feature selection, while L2 helps reduce the impact of irrelevant features without eliminating them.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
