Non-Parametric Models are:

       -A non-parametric model is a type of model that does not assume a fixed functional form for the underlying data distribution. 
       -Instead of learning a finite set of parameters (like in parametric models), non-parametric models can adapt their complexity based on the data

Examples of Non-Parametric Models:

    i)k-Nearest Neighbors (k-NN):
          – Stores training data and makes predictions based on nearest neighbors.
    ii)Decision Trees :
          – Can grow dynamically based on data complexity.
    iii)Random Forests:
          – An ensemble of decision trees.
    iv)Support Vector Machines (with Kernel Trick):
          – Uses the data to create flexible decision boundaries.
    v)Kernel Density Estimation (KDE) :
          – Estimates probability distributions without assuming a specific form.

1)Support Vector Regression (SVR) :

         -Support Vector Regression (SVR) is a type of regression model based on Support Vector Machines (SVMs).
         -Unlike standard regression models that aim to minimize the error directly, SVR tries to fit the best hyperplane within a certain margin of tolerance (ε). 
         -It is particularly useful when dealing with small datasets, high-dimensional data, and non-linearity.
When to Use SVR?

        ✅ When data is non-linear (use kernels like RBF).
        ✅ When the dataset is small (SVR works well with limited data).
        ✅ When you want robustness to outliers (controlled by C and ε).
        ✅ When prediction accuracy is more important than interpretability.

2) Decision Tree(DTR):
   
       -A Decision Tree is a supervised learning algorithm used for classification and regression tasks.
       - It works by recursively splitting the dataset into subsets based on feature values, forming a tree-like structure.

       -Each node in the tree represents a decision rule, and each branch corresponds to an outcome of that rule. 
        -The process continues until the data is classified, or a stopping condition is met.

  Key Terminologies in Decision Trees:
  
        *Root Node: The starting point of the tree, representing the entire dataset.
        *Internal Nodes: Nodes that split into branches based on decision criteria.
        *Leaf Nodes: Terminal nodes representing the final output (classification or regression value).
        *Depth of Tree: The longest path from the root node to a leaf node.
        *Pruning: The process of reducing tree size to avoid overfitting.

 When to Use Decision Trees?
 
        ✅ When interpretability is important (e.g., medical diagnoses).
        ✅ When the dataset contains both categorical and numerical features.
        ✅ For feature selection – Decision trees can identify the most important features.
        ✅ For quick training and inference on small-to-medium datasets.

3)Random Forest Regression(RFT):

      - Random Forest is a supervised learning algorithm that combines multiple decision trees to create a more accurate and robust predictive model.
      -It is commonly used for both classification and regression tasks.

      -Instead of relying on a single decision tree, Random Forest builds multiple trees and combines their results to reduce overfitting and improve accuracy.

Key Hyperparameters in Random Forest:

      🔹 n_estimators – Number of trees in the forest.
      🔹 max_depth – Maximum depth of individual trees (prevents overfitting).
      🔹 min_samples_split – Minimum samples required to split a node.
      🔹 min_samples_leaf – Minimum samples required at a leaf node.
      🔹 max_features – Number of features considered at each split (e.g., "sqrt" for classification).
      🔹 bootstrap – Whether to use bootstrap sampling (True by default).

When to Use Random Forest?

      ✅ When you need high accuracy and are okay with slower training.
      ✅ When dealing with imbalanced datasets (tuning class weights helps).
      ✅ When you have missing data or a mix of categorical and numerical features.
      ✅ When interpretability is not a major concern.



