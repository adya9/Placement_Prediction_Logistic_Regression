# Student Placement Prediction using Logistic Regression

This project demonstrates the use of Logistic Regression to predict student placement based on their CGPA (Cumulative Grade Point Average) and IQ (Intelligence Quotient).

## Project Steps:

1.  **Preprocessing + EDA + Feature Selection**: Initial data cleaning, exploratory data analysis, and selection of relevant features (CGPA and IQ).
2.  **Extract Input and Output Cols**: Separating the independent variables (CGPA, IQ) from the dependent variable (placement).
3.  **Scale the Values**: Standardizing the input features using `StandardScaler` to improve model performance.
4.  **Train Test Split**: Splitting the data into training and testing sets for model evaluation.
5.  **Train the model**: Training a Logistic Regression model on the scaled training data.
6.  **Evaluate the model**: Assessing the model's performance using metrics like accuracy score.
7.  **Deploy the model (Conceptual)**: Saving the trained model using `pickle` for potential deployment.

## Dataset:

The dataset used in this project is `placement.csv`, which contains information about student CGPA, IQ, and their placement status.

## Libraries Used:

*   `numpy`: For numerical operations.
*   `pandas`: For data manipulation and analysis.
*   `matplotlib`: For data visualization (e.g., scatter plot).
*   `sklearn`: For machine learning tasks (data splitting, scaling, model training, evaluation).
*   `mlxtend`: For plotting decision regions (visualizing the model's decision boundary).
*   `pickle`: For serializing and saving the trained model.

## How to Run the Notebook:

1.  Make sure you have the necessary libraries installed (`pip install numpy pandas matplotlib scikit-learn mlxtend`).
2.  Ensure the `placement.csv` file is in the correct directory as specified in the notebook.
3.  Run the cells in the notebook sequentially.

## Files:

*   `placement.csv`: The dataset.
*   `Placement prediction.ipynb`: The Jupyter Notebook containing the code.

## Results:

The notebook demonstrates the process of building and evaluating a Logistic Regression model for student placement prediction. The accuracy score on the test set is also calculated and displayed. A decision boundary plot is generated to visualize how the model separates the two classes.

## Future Improvements:

*   Explore other classification models (e.g., SVM, Decision Tree, Random Forest) and compare their performance.
*   Perform more extensive feature engineering or selection.
*   Implement cross-validation for more robust model evaluation.
*   Build a simple web application to deploy the trained model and make predictions.
