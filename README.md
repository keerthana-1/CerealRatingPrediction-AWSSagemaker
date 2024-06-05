# Cereal Rating prediction - AWS Sagemaker

Data: https://www.kaggle.com/datasets/crawford/80-cereals?resource=download

1. Read the data stored in an S3 bucket using boto3 library.
2. Perform preprocessing steps such as cleaning, handling missing values, and feature engineering. Visualize the data using libraries like Matplotlib or Seaborn to gain insights.
3. Split the preprocessed data into training and testing sets using train_test_split from Scikit-learn.
4. Store the train and test data in two separate files (e.g., CSV format) and upload them to the S3 bucket.
5. Create a machine learning model using Scikit-learn, TensorFlow, or another framework suitable for your problem.
6. Write a script using the AWS SDK or Boto3 to start a training job on Amazon SageMaker, specifying the training data location, model type, hyperparameters, etc.
7. After training, create a copy of the trained model for deployment.
8. Deploy the model using Amazon SageMaker's deployment features and create an endpoint to serve predictions.
9. Use the endpoint to make predictions on new data.
10. Once you're done using the endpoint, delete it to avoid incurring unnecessary costs.




