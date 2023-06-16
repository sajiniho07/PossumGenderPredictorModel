# Possum Gender Predictor Model

This is a Python notebook that builds and tests several models to predict the sex of a possum based on physical characteristics. The dataset used in this model is available in the file `possum.csv`.

The following steps are performed in the code:

1. Read the data from the file `possum.csv`.
2. Encode characters to numbers using LabelEncoder.
3. Fill NaN values with the mean.
4. Equalize the data based on the output data (sex).
5. Separate features into X and Y variables.
6. Normalize the X data using StandardScaler.
7. Split data into train and test sets.
8. Initialize a model callback using EarlyStopping.
9. Define Dense neural network model architecture.
10. Train the model using fit method.
11. Predict the output using the trained model.
12. Evaluate the performance of the model using classification report, confusion matrix, and scatter plots.

Finally, four models with different architectures and hyperparameters were built and tested to find the best fitting model for the given data.

## Requirements

- pandas
- numpy
- sklearn
- keras
- matplotlib

## How to use

To use this model, follow these steps:

1. Install all required packages.
2. Download the `possum.csv` file and place it in your working directory.
3. Copy the entire code in a `.ipynb` file or Jupyter notebook.
4. Run the code block by block.

## Conclusion

This model was able to predict the sex of a possum with an accuracy of around 80% for the given dataset. Four models with different architectures and hyperparameters were built, and the one with the highest accuracy was chosen as the best fitting model. This model can be used as a starting point for further improvements and fine-tuning to increase its prediction accuracy.
