CodeAlpha Iris Flower Classification

Project Overview

This project focuses on classifying Iris flowers into three species:
Iris-setosa, Iris-versicolor, and Iris-virginica.
The classification is performed using the K-Nearest Neighbors (KNN)
machine learning algorithm based on four flower measurements:
Sepal Length, Sepal Width, Petal Length, and Petal Width.
The model is trained using 80% of the dataset and evaluated using
the remaining 20% of the data.

Dataset

The dataset contains 150 flower samples with 50 samples from each species.

Features used:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Methodology

1. Loaded the Iris dataset using Pandas.
2. Checked the dataset structure and data types.
3. Selected the four flower measurements as features.
4. Split the dataset into 80% training and 20% testing data.
5. Trained a K-Nearest Neighbors (KNN) classifier.
6. Evaluated the model using accuracy, classification report, and confusion matrix.
7. Tested the model with a new flower sample.
8. Saved the trained model as `iris_knn_model.pkl`.

Results

- Training samples: 120
- Testing samples: 30
- Model: K-Nearest Neighbors (KNN)
- Accuracy: 100%

The model correctly classified all 30 testing samples in this train-test split.

Visualizations

The project includes:
- Confusion Matrix
- Iris species analysis
- Model evaluation results

Tools and Libraries

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab
