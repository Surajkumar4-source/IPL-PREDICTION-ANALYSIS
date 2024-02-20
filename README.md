# IPL Win Prediction Model

## Introduction
This code implements a simple IPL win prediction model using machine learning. It analyzes historical match data, cleans the dataset, and trains a logistic regression model.
     
  
  This Streamlit web application predicts the probability of winning an IPL match based on various input parameters such as the batting team, bowling team, host city, target score, current score, overs completed, and wickets out.
      

## Prerequisites

- Python 3
- Streamlit library
- Pickle library
- pandas
- scikit-learn



## Data Cleaning and Preprocessing
1. Reads match and delivery data from CSV files.
2. Filters relevant columns and creates a DataFrame for total scores.
3. Handles team name inconsistencies and selects specific teams.
4. Eliminates matches with DL applied.
5. Creates a new DataFrame with essential columns for analysis.

## Feature Engineering
1. Calculates cumulative scores, runs, and wickets for each ball.
2. Computes current run rate (CRR) and required run rate (RRR).
3. Defines a function to determine the match result.

## Model Training
1. Prepares the dataset for training and splits it into training and testing sets.
2. Uses one-hot encoding for categorical variables.
3. Constructs a logistic regression pipeline.
4. Fits the model and evaluates accuracy.

## Streamlit Web App
1. Saves the trained model using pickle.
2. Implements a Streamlit web app for real-time predictions.
3. Allows user input for batting team, bowling team, city, target, current score, overs, and wickets.
4. Displays the win probability for both teams dynamically, with color-coded results.


### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Surajkumar4-source/ipl-win-prediction-streamlit.git


2. Install the required libraries:

        pip install streamlit pandas scikit-learn


3. Run the Streamlit app:

        streamlit run app.py


## Usage

1. **Select Teams and City:**
    - Choose the batting team, bowling team, and host city from the dropdown menus.

2. **Enter Match Details:**
    - Enter the target score, current score, overs completed, and wickets out.

3. **Predict the Outcome:**
    - Click the "Predict Probability" button to get the win probability.





<span style="color:green;">Enjoy predicting IPL match outcomes! 🍀</span>

<br><br>

## DEMO



https://github.com/Surajkumar4-source/IPL-PREDICTION-ANALYSIS/assets/122175764/8dde2f4c-6e94-4e02-af81-76ac355626c5









