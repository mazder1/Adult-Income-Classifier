# US Citizen Income Classifier (Adult Income Classifier)

## Introduction

This project implements a **Multi-Layer Perceptron (MLP)** model designed to predict an individual's income based on demographic and social features. The core task is to determine if a person's annual income is **greater than $50,000 USD** (class `>50K`) or **less than or equal to $50,000 USD** (class `<=50K`).

The model is built with a focus on minimizing external dependencies, utilizing primarily **NumPy** and **Pandas** for both data processing and the fundamental construction of the neural network layers.

### Key Features:

  * **Simple Architecture:** A foundational Multi-Layer Perceptron (MLP) built from scratch.
  * **High Flexibility:** Modular design allowing for easy modification of layer sizes and depths.
  * **Real-World Data:** Trained on the widely recognized *Adult* dataset from the UCI Machine Learning Repository.

-----

## ⚙️ Model Architecture

The project employs a **Multi-layer, fully connected Multi-Layer Perceptron (MLP)**. This classic architecture is known for its versatility in modeling non-linear relationships within data.

### Network Structure

The model consists of the following layers, from input to output:

### Technologies Used (Tech Stack)

  * **Language:** Python 3
  * **Core Libraries:**
      * **NumPy:** Used for all core numerical matrix operations and layer implementation.
      * **Pandas:** Used for efficient data handling and cleaning.
      * **Scikit-learn:** Used solely for the `train_test_split` functionality.

-----

## 💾 Dataset and Preprocessing

### The Adult Dataset (UCI)

The model is trained on the publicly available **Adult Dataset** from the UCI Machine Learning Repository.

  * **Data Source:** [Adult Data Set (UCI Machine Learning Repository)](https://archive.ics.uci.edu/ml/machine-learning-databases/adult/adult.data)

### Data Columns

The input data includes 15 features:
`'age', 'workclass', 'fnlwgt', 'education', 'education-num', 'marital-status', 'occupation', 'relationship', 'race', 'sex', 'capital-gain', 'capital-loss', 'hours-per-week', 'native-country', 'income'`

### Preprocessing Steps

  * Categorical variables were converted into numerical vectors using **One-Hot Encoding**, resulting in **96 features** for the model's input layer.
  * All data is in a `float` format.

-----

-----

## 📊 Results and Evaluation

The current performance metrics for the model are yet to be fully benchmarked.

| Metric | Value |
| :--- | :--- |
| **Accuracy** | ***74*** |
| **Other Metrics** | *To be added soon* |

-----

## 🤝 Contribution and Licensing
### Contributions
Learned from:
https://www.coursera.org/specializations/deep-learning

### License

This project is released under the highly permissive **MIT License**.

### Contact

  * **Miłosz Figura** - [LinkedIn](https://www.linkedin.com/in/mi%C5%82osz-figura-593822397/)
  * **Email:** ***miloszfigurapl@gmail.com***
