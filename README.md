# IMDB-Sentiment-Analysis-Web-App-


Using Amazon's SageMaker service to construct a random tree model to predict the sentiment of a IMDB movie review.

Steps involved in the process:

1. Download or otherwise retrieve the data.
2. Process / Prepare the data.
3. Upload the processed data to S3.
4. Train a chosen model.
5. Test the trained model (typically using a batch transform job).
6. Deploy the trained model.
7. Use the deployed model through Web App.

Setted up AWS Lambda and AWS API Gateway in order to deploy model through model endpoint.
