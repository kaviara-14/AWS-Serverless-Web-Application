# AWS Serverless-Web-Application

*** Setting up an S3 Bucket *** : We'll create an S3 bucket to host our static web content, including HTML, CSS, and JavaScript files.

2. Configuring API Gateway: You'll learn how to configure API Gateway endpoints to trigger Lambda functions. We'll cover both GET and POST methods to interact with our DynamoDB database.

3. Creating Lambda Functions: We'll write Lambda functions in Python to handle the API Gateway requests. For example, we'll create functions to retrieve data from DynamoDB and insert new data into it.

4. Working with DynamoDB: We'll set up a DynamoDB table to store our data. You'll learn how to define the table schema and perform CRUD operations using Lambda functions.

5. Implementing Secure Connections with CloudFront: To ensure secure access to our web application, we'll deploy CloudFront as a content delivery network (CDN). We'll configure CloudFront to serve our S3 content securely over HTTPS, providing encryption in transit and improving the performance of our application.
