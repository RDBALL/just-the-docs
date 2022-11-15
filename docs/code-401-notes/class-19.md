---
layout: default
title: Code 401 | Class 19
parent: Code 401 Notes
---

Reading

[AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

* What is the difference betweeen SQS and SNS?
  * SQS holds messages inside of a queue which can then be distributed to users at the user's request. Users subscribe to SNS topics are are automatically sent topic updates when they are published by the SNS
* What are some use cases for both SNS and SQS?
  * SNS is useful when users are not overly concerned with receiving things in the correct order. SQS can guarantee that information sent to a user is in the desired order.

[AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)

* Describe how to use SQS and SNS in a “fanout” pattern.
  * This term is used to describe how subscribers of SNS topics can receive information in a variety of ways such as e-mail, or SMS push notifications.
* Explain how “push notifications” work, using SNS.
  * Push notifications work if the SNS topic is initialized as a SMS push topic. When something is published within that topic, any subscribers will receive a push notification

[SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)

* How might a large scale, distributed application make use of a Queue system like SQS?
  * SQS allows for a highly scalable queue service that can grow in tandem with your application needs. 

