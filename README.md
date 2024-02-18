### Insurance Prediction using CNN

The "Insurance Prediction using CNN" repository demonstrates the application of Convolutional Neural Networks (CNNs) for predicting insurance outcomes based on features such as age, affordability, and insurance purchase history.

#### Dataset
The dataset comprises the following columns:
- **age**: Age of the individual.
- **affordability**: Affordability status of the individual.
- **bought_insurance**: Indicates if the individual purchased insurance.

#### Workflow Overview
1. **Importing Data**: The dataset is loaded into a DataFrame for analysis.
2. **Data Splitting**: The dataset is split into training and test sets for model training.
3. **Data Scaling**: Age values are scaled between 0 and 1 for model training.
4. **Model Building**: A neural network model is defined using Keras with a single dense layer and a sigmoid activation function.
5. **Model Training**: The model is compiled with the Adam optimizer and binary cross-entropy loss, then trained on scaled data for 5000 epochs.
6. **Model Evaluation**: The model's performance is evaluated on the test set, achieving 100% accuracy.
7. **Prediction**: Model predictions are made on the test set, indicating the likelihood of insurance purchase.
8. **Visualization**: A scatter plot is created to compare actual vs. predicted values.

This repository serves as a learning resource to showcase the effectiveness of CNNs in predicting insurance outcomes based on provided data features.
