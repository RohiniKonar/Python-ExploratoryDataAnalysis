# Python - Exploratory Data Analysis

Below is the description of what the python program is doing:

  Exploratory Data Analysis (EDA):
  1. Reads the dataset from the "parkinson_sample.csv" file using pd.read_csv().
  2. Prints a summary of the dataset using df.describe().
  3. Checks for missing values in the dataset using df.isna().sum().
  4. Plots a histogram of the "total_UPDRS" column using data.hist().
  5. Creates a correlation heatmap of all numerical attributes using sns.heatmap().
  6. Plots a scatter plot of "Jitter(%)" vs. "Jitter:RAP" using sns.regplot().
  7. Creates a box plot of "total_UPDRS" grouped by gender using df_sex.boxplot().
  8. Plots a line plot of "total_UPDRS" vs. "test_time" for different subjects using sns.lineplot().
  
  Clustering:
  1. Visualizes outliers in different feature groups using box plots.
  2. Applies different scalers (StandardScaler and RobustScaler) to columns with and without outliers.
  3. Performs clustering using the KMeans algorithm with different numbers of clusters.
  4. Visualizes the clustering results using scatter plots.
  5. Applies the elbow method to determine the optimal number of clusters.
  
  Predictive Modeling:
  1. Builds and evaluates three different regression models: Random Forest, Linear Regression, and Support Vector Machines (SVM).
  2. Uses pipelines and grid search with cross-validation to find the best model hyperparameters.
  3. Stores the best model and its parameters for later use.
  4. Compares the performance of the models on the test set using evaluation metrics such as mean squared error (MSE), mean absolute error (MAE), and              R-squared score.

    
