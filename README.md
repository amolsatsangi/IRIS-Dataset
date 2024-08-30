# IRIS Dataset Classification

This project demonstrates a simple classification of the IRIS dataset using two different machine learning algorithms: Logistic Regression and K-Nearest Neighbors (KNN). The notebook walks through the entire process, from data loading and preprocessing to model training and evaluation.

## Project Structure

- **Data Preprocessing**: The dataset is split into features (`X`) and labels (`Y`). The data is then divided into training and testing sets with a 80/20 split.
  
- **Model Training**:
  - **Logistic Regression**: A logistic regression model is trained using the training dataset.
  - **K-Nearest Neighbors**: A KNN model is also trained using the training dataset.

- **Model Evaluation**:
  - The accuracy of each model is computed on the test dataset.
  - Both models achieved an accuracy of approximately 96.67%.

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:

- Python 3.x
- Scikit-learn
- Pandas
- Jupyter Notebook (if you want to run the notebook interactively)

You can install the required packages using pip:

```bash
pip install scikit-learn pandas jupyter
