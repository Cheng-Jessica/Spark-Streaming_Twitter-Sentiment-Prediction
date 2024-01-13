# Spark-Streaming_Twitter-Sentiment-Prediction

## Overivew
This project focuses on training a Naive Bayes model for Twitter sentiment prediction using a labeled dataset from Kaggle. The approach involves downloading the dataset, performing data cleaning and target variable transformation, defining and fitting a machine learning pipeline, training the pipeline, obtaining accuracy metrics, saving the model, and testing its performance.

## Dataset (https://www.kaggle.com/datasets/kazanova/sentiment140)
This is the sentiment140 dataset. It contains 1,600,000 tweets extracted using the twitter api . The tweets have been annotated (0 = negative, 4 = positive) and they can be used to detect sentiment .


## Project Structure
1. Download and Explore Data
2. Data Cleaning and Target Variable Transformation
3. Define and Fit an ML Pipeline
4. Save the mode and Test the Saved Model
5. Next Step: Utilize the Saved Model for Sentiment Prediction

## How to Use
- Clone the repository to your local machine.
- Set up your PySpark environment to execute the provided Jupyter Notebooks or scripts.
- Download the required dataset from the provided link.

Contributions are welcome! If you have improvements, optimizations, or additional analyses to suggest, feel free to submit pull requests. 

## Acknowledgments
We acknowledge the Kaggle community for providing the sentiment140 dataset, and the PySpark community for developing powerful tools for scalable data processing and analysis.

Citation: Go, A., Bhayani, R. and Huang, L., 2009. Twitter sentiment classification using distant supervision. CS224N Project Report, Stanford, 1(2009), p.12.
