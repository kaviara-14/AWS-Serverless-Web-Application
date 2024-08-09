# AWS Serverless-Web-Application

Hosted a web application using Amazon S3 buckets with static website hosting and configured API Gateway to trigger Lambda functions for handling GET and POST requests, which interact with a DynamoDB database for data operations. Additionally, I set up CloudFront to serve the S3 content securely over HTTPS, ensuring both enhanced performance and security for the application.



<img src="https://github.com/user-attachments/assets/baa81f37-43ca-4855-8426-3929b1f5ba88">


**AWS Services :** CloudFront, S3, Lambda, DynamoDB, API Gateway, IAM.

## Project Description

### 1. Setting up an S3 Bucket
We'll start by creating an Amazon S3 bucket to store and host the static files for our web application. This includes HTML, CSS, and JavaScript files that make up the frontend of our application. S3 will provide a scalable and reliable storage solution for serving these static assets.

<img src="https://github.com/user-attachments/assets/d4fe8598-76c3-4491-a8ee-c48b3e03ac54">

### 2. Configuring API Gateway
Next, we'll set up Amazon API Gateway to create and manage API endpoints that will interface with our Lambda functions. We'll configure both GET and POST methods to interact with a DynamoDB database, enabling the frontend to perform operations such as retrieving and submitting data.

<img src="https://github.com/user-attachments/assets/8f0a2ce1-2300-4ce0-9893-59a5146f3503">

### 3. Creating Lambda Functions
We'll develop AWS Lambda functions in Python to handle the API requests initiated by API Gateway. These functions will be responsible for interacting with the DynamoDB database, performing operations like retrieving data and inserting new entries based on the requests received.

<img src="https://github.com/user-attachments/assets/1fb0f5fd-40e8-4a01-a3ad-6b857fd14846">

### 4. Working with DynamoDB 
We’ll establish a DynamoDB table to store our application data. This involves defining the table schema (such as partition keys and attributes) and learning how to execute CRUD (Create, Read, Update, Delete) operations using the Lambda functions we’ve created. DynamoDB will serve as the backend database for storing and managing our data.

<img src="https://github.com/user-attachments/assets/4733e336-abe2-47fd-9c0e-1b69e7f14a19">


### 5. Implementing Secure Connections with CloudFront 
To secure our web application and enhance its performance, we'll use Amazon CloudFront as a content delivery network (CDN). CloudFront will be configured to serve the content from our S3 bucket over HTTPS, ensuring encrypted connections and improving the loading speed of our website through distributed caching.


<img src="https://github.com/user-attachments/assets/2ffaaa6d-8306-4327-8280-f737abf67113">

### 6. Final Output
<img src="https://github.com/user-attachments/assets/7e7efd64-790b-45e9-afa5-4cd8504a3022">
