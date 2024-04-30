# Cricket-Player-Performance-Prediction

## Overview

This project focuses on predicting the performance of cricket players, specifically in terms of batting and bowling. It utilizes machine learning models, including RandomForestClassifier for batting prediction and Support Vector Machine (SVM) for bowling prediction.

## Project Structure

The project is organized into several components:

1. **Data Loading:**
   - Player details and match details are loaded from Excel files (`overall_batsman_details.xlsx`, `match_batsman_details.xlsx`, `overall_bowler_details.xlsx`, `match_bowler_details.xlsx`).

2. **Data Preprocessing:**
   - Categorical features are encoded and standardized using LabelEncoder and StandardScaler.
   - Features like opposition, venue, innings played, and historical statistics are processed for model input.

3. **Model Selection:**
   - RandomForestClassifier is employed for batting prediction.
   - Support Vector Machine (SVM) is used for bowling prediction.

4. **Hyperparameter Tuning:**
   - GridSearchCV is applied to find the optimal hyperparameters for both models.

5. **User Interaction:**
   - Users can choose between batting and bowling predictions through a user-friendly interface.
   - The program collects user inputs and provides predictions accordingly.

6. **Result Visualization:**
   - Currently, the project focuses on providing textual outputs for predictions.
