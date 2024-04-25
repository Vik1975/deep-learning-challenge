# Deep-learning-challenge
# Report
# Explain the purpose of this analysis.
The goal of this project is to create an algorithm using machine learning and neural networks to predict whether applicants will be successful if funded by the fictional non-profit foundation, Alphabet Soup.
# Results
# Data Preprocessing
- The target variable is the 'IS_SUCCESSFUL' column from application_df
- The feature variables are every other column from application_df --> this was defined by dropping the 'IS_SUCCESSFUL' column from the original dataframe
- 'EIN', 'NAME','SPECIAL_CONSIDERATIONS','USE_CASE','ASK_AMT' were removed, because they were neither targets nor features for the dataset.
# Compiling, Training, and Evaluating the Model
- In the first attempt, I used two layers with 9 and 18 neurons respectively. The number was chosen randomely for the first try.
- I was not able to achieve 75% goal. All three attemptes gave me the rersult near 73%
- I added more layers, more neurons and deleted more columns after failing the first attempt
# Summary
In the three attempts I made, the model was unable to achieve a target predictive accuracy higher than 73%. Hypertuning resulted in virtually no improvement. I would consider using another classification model to see if it is better at predicting whether applicants will be successful if funded by Alphabet Soup.

