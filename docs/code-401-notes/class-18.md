---
layout: default
title: Code 401 | Class 18
parent: Code 401 Notes
---

## Readings: AWS: API, Dynamo and Lambda

[AWS API Gateway Overview](https://www.serverless.com/amazon-api-gateway)

* What is Amazon API Gateway?
  * Amazon API Gateway is an AWS service for creating, publishing, maintaining, monitoring, and securing REST, HTTP, and WebSocket APIs at any scale.
* Why is Amazon API Gateway an important part of the Serverless ecosystem?
  * The Amazon API Gateway enables the serverless functions to be tied to the API definitions
* How does API Gateway integrate with other AWS services?
  * AWS Lambda: run Lambda functions to generate HTTP API responses.
  * AWS SNS: publish SNS notifications when an HTTP API endpoint is accessed.
  * Amazon Cognito: provide authentication and authorization for your HTTP APIs

[AWS API Gateway](https://aws.amazon.com/api-gateway/)

* What are some benefits of using Amazon API Gateway?
  * Consistent performance at any scale, efficient deployment of APIs
* What two API types might you choose from?
  * RESTful and Websocket

[AWS DynamoDB Guide](https://www.dynamodbguide.com/what-is-dynamo-db/)

* What is DynamoDB?
  * This is a NoSQL database offered by AWS
* Under what circumstances would you recommend DynamoDB over MongoDB?
  * If there is the expectation that the service requiring a database will scale exponentially or should be able to scale exponentially, DynamoDB offers enterprise level support and infrastructure that you can take advantage of.

[AWS DynamoDB](https://aws.amazon.com/dynamodb/)

* Explain to a non-technical friend how DynamoDB works.
  * DynamoDB is a serverless database that is available for applications that need scalability and speed. Specifically, this DB provides read capabilities at speeds equaling to 1 response per second of highly accurate data. This can be increased to multiple responses per second of not as accurate data.

[Dynamoose](https://dynamoosejs.com/getting_started/Introduction)

* What is Dynamoose?
  * Dynamoose is a tool that can be used like mongoose for creating data but specific to DynamoDB
* What are some key features of Dynamoose?
  * Support for multiple AWS regions, high level API, supports DynamoDB single table design
