# medium-simple-java-lambda

This project is meant to be an example of how to create and deploy an AWS Lambda function 
written in Java. The Lambda function simply returns the string "Hello World!".
There is no trigger defined for the lambda so it can only be invoked by using the Test feature in
the AWS Lambda console or via the SAM CLI.

The [Medium.com article](https://medium.com/@paulboeck/deploying-an-aws-lambda-with-sam-d8dc2be798e3?source=friends_link&sk=6b50fc2b83a642898464360f39a32bdf)

## Assumptions
- you have installed the AWS CLI and configured it with your AWS credentials
- you have installed SAM CLI
- you have created an S3 bucket to store the Lambda function package
- Commands in this document are specified for a Linux or Mac OS X environment. If you are using
  Windows, you will need to adjust the commands accordingly.
