# **Ticket Cancellation Predictor**

## **Overview**

This project implements a **Ticket Cancellation predictor** using various machine learning models. It aims to predict whether a ticket will be canceled based on a set of features. The implemented models include **Random Forest**, **XGBoost**, **Gradient Boosting**, and **LightGBM**. The project uses Python and popular machine learning libraries such as scikit-learn, XGBoost, LightGBM, and others.

## **Project Structure**

- `code.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
- `requirements.txt`: List of Python packages required to run the project.
- `data/`: Directory containing the dataset used for training and testing.
- `README.md`: This file, providing an overview of the project, instructions, and information on how to run the code.

## **Setup**

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ticket-cancellation-predictor.git
2. install dependcies

    ```pip install -r requirements.txt```
3. Open and run the code.ipynb notebook using Jupyter or any compatible environment.

## **Usage**
1. Open the Jupyter Notebook (ticket_cancellation_predictor.ipynb).
2. Run the notebook cells sequentially to perform data preprocessing, model training, and evaluation.

## **Training** 
The models in this project were trained using the dataset available at [Kaggle - Ticket Cancellation Prediction Final](https://www.kaggle.com/competitions/ticket-cancellation-prediction-final). The dataset includes features related to ticket information and cancellation status, which were used to train and evaluate the machine learning models.

## **Results**
The notebook will print the F1-Score and Accuracy for each model on the test set. The best-performing model will be highlighted, and the selected model will be assigned to the 'model' variable for further use. 
