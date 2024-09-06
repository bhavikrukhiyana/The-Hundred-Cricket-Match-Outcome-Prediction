# The Hundred Cricket Match Outcome Prediction

This repository contains the code and resources for a machine learning project aimed at predicting match outcomes in The Hundred cricket league.

## Project Overview

The Hundred is a novel cricket format introduced by the England and Wales Cricket Board. This project uses machine learning techniques to predict match outcomes based on player performance metrics and team statistics.

## Key Features

- Data collection and preprocessing of ball-by-ball data from 187 matches
- Feature engineering incorporating both player-level and team-level statistics
- Implementation of Random Forest and Support Vector Machine models
- Gender-specific analysis of prediction performance
- Evaluation of model generalization to future season data

## Data

The data used in this project was sourced from cricsheet.org, covering matches from the 2021-2023 seasons of The Hundred. Link: https://cricsheet.org/downloads/hnd_json.zip

## Methodology

1. Data Collection and Preprocessing
2. Feature Engineering
3. Model Development (Random Forest and SVM)
4. Hyperparameter Tuning
5. Performance Evaluation
6. Gender-based Analysis

## Results

- High accuracy on the test set for both models
- Significant disparity in performance between men's and women's matches
- Identification of key features influencing match outcomes

## Future Work

- Mitigation of overfitting in the Random Forest model
- Incorporation of additional contextual factors (e.g., weather, pitch conditions)
- Development of in-game prediction capabilities
- Exploration of deep learning approaches

## Requirements

- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Usage

This project consists of several Jupyter notebooks that guide you through the process of data extraction, exploration, feature engineering, and model development for The Hundred cricket match outcome prediction.

1. **Data Extraction**:
   - Run `Extracting Data from JSON files.ipynb` to extract match details from JSON files and create a DataFrame.
   - This script generates `hundreds_extracted_data_with_match_stats.csv`, which is used in subsequent steps.

2. **Initial Exploratory Data Analysis**:
   - Execute `Exploring Features For Computing Performance Probability.ipynb` for initial insights and analysis.

3. **Feature Engineering and Performance Probability Calculation**:
   - Run `Final Features for Calculating Performance Probability - Batsmen, Bowlers, Team - 1.ipynb` for computing probability scores on batting and bowling performance for both male and female players.
   - Follow up with `Final Features for Calculating Performance Probability - Batsmen, Bowlers, Team - 2.ipynb` for team performance probability scores.

4. **Visualizations**:
   - Use `Visualizations.ipynb` to generate key visualizations for the project.

5. **Model Development and Evaluation**:
   - Execute `Final Model & Validation.ipynb` for model development, analysis visualizations, and evaluation on 2024 match data.

## Contributors

- Bhavik Rukhiyana

## Acknowledgements

This project was completed as part of a dissertation at Durham University. Special thanks to supervisor Fred Worall for guidance throughout the project.
