## 📌 Overview  
Softmax Regression is a classification algorithm used when the target variable has multiple classes. It extends logistic regression to handle multi-class classification problems by assigning probabilities to each class.  


## 📚 Prerequisites  
- Knowledge of linear algebra (matrix multiplication, dot product)  
- Understanding of logistic regression and gradient descent  
- Familiarity with NumPy for numerical computations  

## ✅ Key Topics Covered  
✔️ **Forward Pass**: Computing logits  
✔️ **Applying Softmax**: Converting logits into probabilities  
✔️ **Cross-Entropy Loss**: Measuring the model’s performance  
✔️ **Gradient Computation**: Using backpropagation to compute gradients  
✔️ **Weight Updates**: Applying gradient descent to update parameters  
✔️ **Visualization**: Decision boundary and loss reduction 



## 📂 Project Structure

Softmax_Regression_from_Scratch/
│-- Notebooks/
│ ├── Softmax_regression.ipynb
│ ├── accuracy.txt
│-- Images/
│ ├── loss_plot.png
│ ├── decision_boundary.png
│-- requirements.txt
│-- README.md



You can run the notebook step by step to understand how Softmax Regression works. Each section is explained with clear code and mathematical derivations.



## 📊 Results & Visualization

### 🔹 Accuracy
The final accuracy of the Softmax Regression model:

**🔥 Accuracy: 90 %**

### 🔹 Loss Reduction
The model's loss decreases over time, indicating successful learning.

![Loss Plot](Images/loss_plot.png)

### 🔹 Decision Boundary
The decision boundary visualization shows how the model classifies different regions.

![Decision Boundary](Images/decision_boundary.png)