# Serverless-private-URL-shortener
based on Amazon S3, AWS Lambda, Amazon CloudFront and API Gateway.

Run the cloudformation tempalte to build a pretty ugly short url

Register a domain and setup r53 AAAA alias record to the cloudfront distribution

Update the cloudformaiton distribution to include the alias

get an ACM cert to clear the ssl cert error on the browser

TODO: setup basic-auth in front of hte url so that it is not open to the public
TODO: automate this vs running and doing all the steps manually
TODO: update the bucket policy and setup a redirect on the root of the bucket to the long name of the url path
