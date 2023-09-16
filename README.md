# Election Sentiment Analysis with Machine Learning and Twitter Data

## Overview

This project performs sentiment analysis on Twitter data related to two political figures, Narendra Modi and Rahul Gandhi. It uses machine learning techniques to classify tweets as positive, negative, or neutral based on their sentiment.

## Steps to Run the Project

Follow these steps to set up and run the project on your local machine:

1. **Download Datasets**:
   - Download the datasets for tweets related to Narendra Modi and Rahul Gandhi. Ensure they are in CSV format and named 'modi.csv' and 'rahul.csv'.
   - Save these datasets to your project directory.

2. **Install Dependencies**:
   - Ensure you have Python and the required libraries installed. You can install the necessary libraries using pip:
     ```
     pip install pandas numpy scikit-learn textblob wordcloud plotly seaborn matplotlib
     ```

3. **Open Jupyter Notebook**:
   - Launch Jupyter Notebook by running the command:
     ```
     jupyter notebook
     ```

4. **Run the Code**:
   - Open the Jupyter Notebook file containing the code from your project directory.
   - Execute the code cells one by one, following the comments and instructions provided in the notebook.
   - The code includes the following sections:

   - **Data Preparation**:
     - Load and preprocess the Twitter data for Narendra Modi and Rahul Gandhi.
     - Perform sentiment analysis using TextBlob and calculate sentiment polarity.

   - **Machine Learning Models**:
     - Train Multinomial Naive Bayes and Decision Tree classifiers for sentiment analysis.
     - Evaluate the models and display accuracy and confusion matrices.

   - **Data Visualization**:
     - Generate word clouds and visualizations to analyze sentiment distribution.

5. **Interact with the Results**:
   - Explore the generated visualizations and results to gain insights into sentiment trends related to the two political figures.

## Additional Notes

- You can customize the project by replacing the provided datasets with your own Twitter data or by exploring different machine learning algorithms for sentiment analysis.
- Feel free to reach out if you have any questions or need further assistance with the project.

Happy analyzing!
