# Iris Flower Classification with k-NN

## Introduction
This project demonstrates the implementation of the **k-Nearest Neighbors (k-NN)** algorithm, a popular machine learning algorithm, using the famous **Iris Flower dataset**. The goal is to classify different types of iris flowers based on their features such as sepal length, sepal width, petal length, and petal width.

## Dataset
The Iris Flower dataset contains 150 records, each representing an iris flower belonging to one of three species:
1. Iris Setosa (Class 0)
2. Iris Versicolor (Class 1)
3. Iris Virginica (Class 2)

Each flower has four features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

![iris_types](https://github.com/user-attachments/assets/972349fc-38fe-4e13-bc86-e9bc0d667b00)

The dataset is loaded from two `.npy` files:
- `irises.npy`: Contains the feature data of the flowers.
- `types.npy`: Contains the class labels for the flowers.

## Features
- **Algorithm**: k-Nearest Neighbors (k-NN)
- **Data**: Processed from the Iris Flower dataset
- **Language**: Python
- **Libraries**: Numpy, SciPy

## Running the Notebook
To run the code, follow these steps:
1. Make sure you have installed the required dependencies by running:
   ```bash
   pip install numpy scipy
2. Open the Jupyter notebook iris_flowers.ipynb.
3. Run all the cells to load the dataset, process the data, and classify the iris flowers using the k-NN algorithm.

## Output
The notebook prints out the predicted classes of the iris flowers, compares them with the actual class labels, and calculates the accuracy at the end.

## Contribution
If you'd like to contribute to this project, feel free to open a pull request or report issues in the issue tracker
