| **Feature**               | **ID3**                       | **C4.5**                          | **CART**                           |
|----------------------------|-------------------------------|------------------------------------|-------------------------------------|
| **Developer**              | Ross Quinlan                 | Ross Quinlan                      | Breiman et al.                     |
| **Splitting Criterion**    | Information Gain             | Gain Ratio                        | Gini Impurity (Classification),<br> Mean Squared Error (Regression) |
| **Data Types Supported**   | Categorical                  | Categorical & Continuous          | Categorical & Continuous           |
| **Pruning**                | No                           | Post-pruning                      | Cost-complexity pruning            |
| **Output**                 | Multi-way splits             | Multi-way splits                  | Binary splits                      |
| **Regression Support**     | No                           | No                                | Yes                                |
| **Handles Missing Data**   | No                           | Yes                               | Yes                                |
| **Computational Efficiency** | Fast                       | Moderate                          | Moderate                           |
| **Bias Towards Features**  | Yes, towards features with<br>many categories | No, uses Gain Ratio to normalize | No                                |
| **Strengths**              | Simple and easy to implement | Handles continuous data,<br>avoids bias, post-pruning | Supports both classification<br>and regression; robust |
| **Weaknesses**             | Overfitting prone,<br>categorical data only | Slower than ID3,<br>no regression | Only binary splits,<br>more computationally intensive |
| **Applications**           | Simple classification tasks<br>(e.g., weather prediction) | Complex classification tasks<br>(e.g., disease diagnosis) | Both classification and regression<br>(e.g., fraud detection,<br>house price prediction) |
