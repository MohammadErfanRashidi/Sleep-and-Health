Link to the dataset: https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset 

# Sleep Health Analysis

This project analyzes a sleep health and lifestyle dataset to understand the factors influencing sleep quality.

## Workflow

1. **Installation:** Install necessary libraries like seaborn and scikit-learn.
2. **Data Loading and Exploration:**
   - Load the dataset from a CSV file.
   - Analyze the data types, view the first few rows, check the shape, identify missing values, and calculate descriptive statistics.
3. **Feature Engineering:**
   - Combine textual features (Gender, Occupation, BMI Category) into a single feature.
   - Select numerical features and convert them to strings.
   - Combine text and numeric features into a single feature set.
   - Convert the combined features into numerical representations using TF-IDF vectorization.
   - Encode the target variable ("Quality of Sleep").
4. **Model Training:**
   - Split the data into training and testing sets.
   - Train a logistic regression model on the training data.
5. **Evaluation:**
   - Evaluate the model's accuracy on both the training and testing data.
6. **Visualization:**
   - Create various visualizations to explore relationships between variables:
     - Heatmap of correlation between features.
     - Scatter plots of sleep duration vs. quality of sleep, and sleep duration/quality with age.
     - Bar plot of occupations with the highest mean BMI.
     - Scatter plot of heart rate vs. sleep duration, with point size representing stress level.

## Note

- The code includes steps to convert categorical variables to numerical representations for analysis and visualization.
- The original categorical values are restored for certain visualizations.
