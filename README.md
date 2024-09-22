# Simple WebSocket Chat Application
This real-time chat application is built using AWS Lambda, API Gateway (WebSocket API), and Amazon DynamoDB. The chat system allows multiple clients to communicate with each other in real time.

# Features
WebSocket API for real-time communication
Serverless architecture using AWS Lambda
Persistent storage of chat messages and connections in DynamoDB
Secure connection management (connect/disconnect handling)
Real-time message broadcast to all connected clients
Building real Time chat application using AWS services

# Architecture Overview
AWS Lambda: Manages the backend logic for connection, disconnection, and message handling.
Amazon API Gateway (WebSocket API): Facilitates real-time bidirectional communication between clients and the server.
Amazon DynamoDB: Stores the connection details and chat messages.
AWS SAM (Serverless Application Model): Used to deploy the infrastructure.

