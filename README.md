# AWS Lambda CI/CD Pipeline

This project sets up a CI/CD pipeline to deploy an AWS Lambda function using GitHub Actions.

## How to Use

1. Set up AWS credentials in your GitHub repository secrets (`AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY`).
2. Push changes to the `main` branch.
3. GitHub Actions will automatically deploy the Lambda function to AWS.

## Lambda Function

The Lambda function makes an HTTP request to GitHub's API and returns the response along with a message.
