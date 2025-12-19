# Event-Driven Payment Processing System

A cloud-native, fault-tolerant payment processing backend built using AWS serverless services and Python.

## 🚀 Features
- Asynchronous payment processing
- Idempotent handling to prevent double payments
- Event-driven architecture using SQS
- Dead Letter Queue for failed events
- DynamoDB for wallet and payment storage
- CloudWatch logging and monitoring

## 🏗 Architecture
Client → API Gateway → Lambda → SQS → Lambda → DynamoDB → SNS

## 🛠 Tech Stack
- Python
- AWS Lambda
- API Gateway
- SQS + DLQ
- DynamoDB
- CloudWatch

## 📸 Screenshots
Screenshots are available in the `/screenshots` directory showing AWS resources and logs.

## 🧠 Key Learnings
- Handling duplicate events
- Designing idempotent APIs
- Distributed system failure handling
- Serverless backend design

## 📦 How to Deploy
Refer to `/infrastructure` folder for step-by-step AWS setup.
# event-driven-payment-system
