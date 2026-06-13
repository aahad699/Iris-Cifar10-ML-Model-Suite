# Iris & CIFAR-10 Machine Learning Model Suite

A compact machine learning project that demonstrates both classical ML and deep learning workflows in a single notebook. The project uses the Iris dataset for regression and classification experiments, then extends into computer vision with a custom PyTorch convolutional neural network trained on CIFAR-10.

The notebook walks through data loading, preprocessing, train/test splitting, model training, evaluation, visualization, and model persistence. It is designed as a portfolio-ready example of practical ML experimentation across structured tabular data and image classification.

## Project Highlights

- Built and evaluated multiple models, including Linear Regression, K-Nearest Neighbors, Decision Tree classification, and a PyTorch CNN.
- Added performance reporting with metrics such as MSE, R2 score, accuracy, confusion matrices, precision, recall, and F1-score.
- Used preprocessing techniques such as feature scaling for distance-based classification.
- Persisted trained model artifacts with `joblib` and PyTorch `state_dict` saving.
- Included custom prediction functions for manual inference on flower measurements and image inputs.

## Models

| Model | Dataset | Task |
| --- | --- | --- |
| Linear Regression | Iris | Predict petal length from flower measurements |
| K-Nearest Neighbors | Iris | Classify Iris species |
| Decision Tree | Iris | Classify Iris species and visualize decision boundaries/tree behavior |
| Convolutional Neural Network | CIFAR-10 | Classify images across 10 object categories |

## Technologies Used

- Python
- Jupyter Notebook / Google Colab
- pandas
- NumPy
- scikit-learn
- PyTorch
- torchvision
- Matplotlib
- Seaborn
- joblib
- PIL

## Repository Structure

```text
.
├── ML_Project.ipynb
├── README.md
└── .gitignore
```

## How to Run

1. Open `ML_Project.ipynb` in Jupyter Notebook or Google Colab.
2. Install the required libraries if they are not already available.
3. Update dataset paths if running outside Google Colab.
4. Run the notebook cells from top to bottom.

## Resume Bullets

- Developed a machine learning model suite using Python, scikit-learn, and PyTorch to perform Iris regression/classification and CIFAR-10 image classification across classical ML and CNN-based deep learning workflows.
- Implemented preprocessing, model training, evaluation, visualization, and artifact persistence with metrics including MSE, R2, accuracy, confusion matrix, precision, recall, and F1-score.
