# 🚀 AWS Lambda + API Gateway + S3 Demo

This project demonstrates how to deploy a simple static website on Amazon S3 that connects to a serverless backend powered by AWS Lambda and API Gateway.

## 📁 Project Structure

aws-lambda-s3-demo/ ├── backend-api/ │ ├── Lambda_function.py │ └── Lambda-trust-policy.json ├── webapp-frontend/ │ ├── index.html │ └── lambda-trust-policy.json


## ☁️ AWS Services Used

| Service          | Description                                    |
|------------------|------------------------------------------------|
| **S3**           | Hosts the static frontend (HTML file)          |
| **Lambda**       | Runs backend logic (Python function)           |
| **API Gateway**  | Connects the frontend to Lambda through an API |
| **IAM**          | Provides access and execution permissions      |
| **CloudWatch**   | Used for logging and debugging                 |

## 🔁 Flow

1. The frontend is hosted in an S3 bucket.
2. When a user clicks the button, it triggers an HTTP request.
3. The request hits API Gateway which invokes the Lambda function.
4. Lambda responds with a message and the frontend displays it.

## 🧪 Example Output

{ "message": "Hello from Lambda" }


## 👨‍💻 Author

Majed Aldughayshim  
[GitHub Profile](https://github.com/imajedkd)  
📧 imajidkd@gmail.com

