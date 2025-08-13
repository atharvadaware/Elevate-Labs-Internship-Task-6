## Iris dataset Classification

1.  **Import Dependencies**: Imported necessary libraries for data manipulation, visualization, and machine learning (numpy, pandas, matplotlib, sklearn).
2.  **Import Dataset**: Loaded the Iris dataset from `sklearn.datasets`.
3.  **Create DataFrame**: Converted the Iris dataset into a pandas DataFrame for easier handling, including the features and target variable.
4.  **Separate Features and Target**: Divided the DataFrame into features (X) and the target variable (y).
5.  **Train/Test Split**: Split the data into training and testing sets to evaluate the model's performance on unseen data. Stratification was used to maintain the proportion of classes in both sets.
6.  **Normalize Features**: Applied StandardScaler to normalize the features, which is often beneficial for distance-based algorithms like K-Nearest Neighbors.
7.  **Experiment with different K values**: Trained and evaluated KNN models with different values of K (1, 3, 5, 7, 9). Calculated the accuracy and displayed confusion matrices for each K to assess performance.
8.  **Identify Best K**: Determined the K value that yielded the highest accuracy.
9.  **Visualize Decision Boundary**: Trained the best performing KNN model and visualized its decision boundaries based on the first two features (Sepal Length and Sepal Width) while keeping the other features at their mean.
