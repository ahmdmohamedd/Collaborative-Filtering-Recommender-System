# Collaborative Filtering Recommender System

This repository contains an implementation of a **Collaborative Filtering Recommender System** using **Singular Value Decomposition (SVD)**. The recommender system predicts personalized recommendations based on user preferences using collaborative filtering techniques. The model is built using the **Surprise** library and demonstrates how to use the **MovieLens** dataset for recommendation tasks.

## Overview

Collaborative filtering is a popular technique used in recommendation systems to suggest items (e.g., movies, books, music) based on user-item interactions. This approach assumes that users who have similar tastes in the past will have similar preferences in the future.

In this project, we use the **SVD (Singular Value Decomposition)** algorithm for collaborative filtering. SVD is a matrix factorization technique that decomposes the user-item interaction matrix into three matrices, which can be used to make predictions.

## Features

- **SVD Model**: Uses Singular Value Decomposition (SVD) for collaborative filtering.
- **RMSE Evaluation**: Evaluates model performance using Root Mean Squared Error (RMSE).
- **Personalized Recommendations**: Provides personalized predictions for users.
- **Top-N Recommendations**: Generates top-N item recommendations for a specific user.
- **MovieLens Dataset**: Uses the MovieLens 100k dataset for training and evaluation.

## Requirements

To run this project, you need to install the following Python libraries:

- **NumPy**
- **Pandas**
- **Surprise** (for building and evaluating the recommendation system)
- **Scikit-learn** (optional for additional utilities)

You can install them using `pip`:

```bash
pip install numpy pandas scikit-learn surprise
```

## How to Use

1. **Clone the Repository**:
   Clone this repository to your local machine:

   ```bash
   git clone https://github.com/ahmdmohamedd/Collaborative-Filtering-Recommender-System.git
   cd Collaborative-Filtering-Recommender-System
   ```

2. **Open the Jupyter Notebook**:
   Open the `collaborative_filtering_recommender_system.ipynb` file in Jupyter Notebook or Google Colab.

3. **Run the Code**:
   Execute the notebook cells step-by-step to build the recommender system:
   - Load and preprocess the MovieLens dataset.
   - Train the SVD model on the training set.
   - Evaluate the model using RMSE.
   - Make personalized predictions and generate top-N recommendations for users.

## Notebook Overview

### 1. Install Required Libraries
The first cell installs all the necessary dependencies.

### 2. Import Libraries
In this step, we import the necessary libraries, such as `Surprise`, `NumPy`, and `Pandas`.

### 3. Load Dataset
The dataset used in this project is the **MovieLens 100k dataset**, which is provided by the Surprise library.

### 4. Prepare Data
We split the dataset into training and test sets for collaborative filtering tasks.

### 5. Build Collaborative Filtering Model
We implement the SVD model using the `Surprise` library and train it on the training set.

### 6. Evaluate the Model
We evaluate the model’s accuracy using the **Root Mean Squared Error (RMSE)**.

### 7. Make Predictions
We demonstrate how to predict ratings for a given user-item pair.

### 8. Top-N Recommendations
We generate top-N recommendations for a specific user based on the predicted ratings.

## Example Output

1. **RMSE**: After evaluating the model, you will see the RMSE value, which indicates how well the model is performing.
2. **Top-N Recommendations**: The notebook provides the top-N recommendations for a given user.

## Contributing

Feel free to fork this repository, submit issues, and make pull requests. Contributions are welcome!
