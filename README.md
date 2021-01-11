# Serverless-architecture
Serverless-architecture aws
Services we will use to create a serverless web page which is being used and popular in the market....
SERVICES:
Lambda
Api-gateway
s3
Route53
Using these we use in demo

Other-services:
Cloudfront
dynamodb
SQS
SNS
SES


Step-1)
Create a lambda in python 3.6 with simple-microservice-permissions
Modify the code with respect to serverless-lambda-code.py mentioned in this repo 

Step-2)
Create an api gateway with the above lambda as target

Step-3)create s3 with public-webhosting configuration with the index.html,error.html files present in this rep

step-4)
you can serve static content from s3 and dynamic content from api-gateway.
As s3 doesn't provide https endpoint , you can use cloudfront for https endpoint.
you can link route-53 directly to s3 or use cloudfront inbetween to serve the webpage
