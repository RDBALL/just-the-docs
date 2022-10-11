---
layout: default
title: Code 401 | Class 16
parent: Code 401 Notes
---
AWS EC2

* What is an EC2 Instance?
  * An EC2 (elastic compute cloud) instance is a virtual machine that can be deployed on the cloud through AWS
* Name 2 use cases for EC2.
  * Depending on what you are trying to accomplish, there are almost 50 EC2 instances that you can chose to deploy
  * A general server that uses cpu, memory and network capabilities in equal amounts would be best suited to an EC2 instance that keeps those three markers aligned.
  * An application that depends on raw compute power may chose and EC2 instance that favors more CPU power over network capabilities or memory
* Provide 1 reason to use ECS instead of Heroku.
  * Enterprise levels of security and support are provided through AWS products.

EC2 For Humans

* Where can we find EC2 on the AWS Console?
  * Search for EC2 and select it from the menu. It is nested in the compute section
* Explain the general difference between T2 Micro and XL.
  * The differ nice between these EC2 instance options is the amount of virtual CPUs and memory that will be available for the instance to use
* Explain a “Compute Cycle” to a non-technical friend.
  * A compute cycle is the process of executing a specific task, from beginning to end. The cycle begins with a request which triggers a function to take in the request and pass it through function specific code. Once the function has executed, the request is then passed to a follow on service where it is either stored in memory or retrieves data from memory. The information is then passed back to the initial requestor in the form of a confirmation message or data that is retired from the request.

Elastic Beanstalk

* What is Elastic Beanstalk?
  * This is a web service provided by AWA that allows individuals to
* Describe the relationship between EC2 and Elastic Beanstalk.
  * Elastic Beanstalk automatically deploys your application using an EC2 instance.
* Name some benefits of using Elastic Beanstalk.
  * Highly scalable depending on need
  * Easy to deploy applications once an application is developed.
  * Offers quick deployment options
  * Supports multi-tenant architecture
  * Highly flexible
  * Accepts multiple development languages
