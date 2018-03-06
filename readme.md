# S3plus

## About
This project demonstrates basic serverless principals to build infrastructure for website hosting in an automated and secure manner that is distributed globally. The cloudformation template is designed to create a secure S3 bucket preconfigured for website hosting.

If the user also has a registered domain name with Amazon the template will:
* Create an SSL certificate.
* Create a CloudFront distribution.
* Create a Route 53 record for your naked domain name to your CloudFront distribution.
* Connect each component properly together.

If desired the user can also:
* Add a subdomain to the certificate.
* Add a subdomain to Route 53 record set and point it to the CloudFront distribution.
