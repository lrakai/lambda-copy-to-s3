# lambda-copy-to-s3
AWS Lambda function to copy files from URLs to an S3 bucket. Used to pre-load S3 buckets in AWS CloudFormation.

* `copy-to-s3.py`: Lambda function to copy files from URLs to a provided S3 bucket
* `cloudformation.json`: Example CloudFormation template that creates an S3 bucket and uses a Lambda-backed custom resource to copy files into the S3 bucket.
