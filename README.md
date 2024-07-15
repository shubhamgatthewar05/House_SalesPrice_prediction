
# House Sales Price Prediction

## Overview
This project aims to predict house sales prices using a linear regression model. The dataset used for training and testing the model is from a Kaggle competition. The project involves data preprocessing, model training, prediction, and evaluation.

## Dataset
The dataset consists of house features and sales prices. It is divided into two parts:
- `train.csv`: Used for training the model.
- `test.csv`: Used for making predictions and creating the submission file.

## Features
The following features are used to predict the house sales price:
- `GrLivArea`: Above grade (ground) living area square feet.
- `BedroomAbvGr`: Number of bedrooms above ground.
- `FullBath`: Number of full bathrooms.
- `HalfBath`: Number of half bathrooms.

## Project Steps
1. **Import Libraries:** Import necessary libraries for data manipulation, model building, and evaluation.
2. **Load Data:** Load the training and test datasets.
3. **Data Preprocessing:** Handle missing values and clean the data.
   - Fill missing values in `LotFrontage` with the median value.
   - Fill missing values in `MasVnrArea` with 0.
4. **Feature Selection:** Select relevant features for the model.
5. **Split Data:** Split the training data into training and testing sets.
6. **Train Model:** Train a linear regression model using the training data.
7. **Make Predictions:** Make predictions on the test set and evaluate the model.
8. **Create Submission File:** Make predictions on the test data and save the results in a submission file.

## Evaluation
The model is evaluated using Root Mean Squared Error (RMSE). The RMSE for the test set is printed as part of the evaluation process.

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <project_directory>
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the project script:
   ```bash
   python house_price_prediction.py
   ```

## Submission
The submission file `submission.csv` contains the predicted house prices for the test dataset.

