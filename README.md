# Decision-Tree-Classifier-with-Banknote-Authentication-Dataset

## Project Description

This project applies a Decision Tree Classifier to the Banknote Authentication dataset using scikit-learn. The dataset contains 4 numerical features and a binary class label (0 = fake, 1 = authentic). The main objective is to build a model that accurately classifies banknotes and explore how different hyperparameters affect model performance.

## Instructions to Run the Code

1. **Clone the repository** or download the project files.
   
   ```bash
   git clone <repository-url>
Install required libraries:

2. You can install the necessary libraries using pip:

   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn ucimlrepo


3. Run the Jupyter Notebook:

Open decision_tree.ipynb in Jupyter Notebook or JupyterLab and execute the cells in order:

The dataset is loaded and split into training and testing sets.

A Decision Tree model is trained with manually chosen parameters.

Model performance is evaluated using accuracy, confusion matrix, and classification report.

Feature importance is visualized and the tree structure is plotted.

4. View the Results:

Accuracy score of the Model
 
Confusion matrix and classification report give detailed performance insights.

Feature importance plot shows which attributes influence classification the most.

The decision tree is visualized for interpretability.

Comparison with GridSearchCV results highlights the difference in selected parameters.

## Conclusion
The Decision Tree model performs exceptionally well on the Banknote Authentication dataset, achieving high accuracy and interpretability. Both manual tuning and GridSearchCV are explored, demonstrating that thoughtful parameter selection can lead to even better results than automated tuning in some cases.
