# Java-Spring RabbitMQ

In this 3 part Lab, I experimented with Spring AMQP Messaging using RabbitMQ, and have covered steps for its deployment to a local docker container, and interacked with the Workers feature to create several queues.

## Messaging with RabbitMQ -  Basic Intro to RabbitMQ with Spring

### Created a RabbitMQ Message Receiver with Spring

### Registered the Listener and Send a Message

### Sent a Test Message

### Configured Application Properties

### Screenshots of Running the Application

![part1](./images/mq-send-rec.png)



## RabbitMQ Tutorial - Hello World - Testing the Messaging feature with Rabbit Console

### Setup Spring Profiles

### Configured the project

### Screenshots for Running the app

- Sending

![message-send](./images/part2-console-send.png)

- Receiving

![message-receive](./images/part2-console-receive.png)

- Rabbit Console

![console](./images/part2-rabbit-console.png)



## RabbitMQ Tutorial - Work Queues - Configuring Queues, and Managing frequency.

### Spring Profiles

### Configuring the project

### Running the app

- Sending
![part3-1](./images/workers-console-send.png)

- Receiving
![part3-2](./images/workers-console-receive.png)

- Rabbit Console
![part3-3](./images/workers-rabbit-console.png)


# Lab Notes Discussion:

- Rabbit Queues can be used in projects, to control the data / transaction flow from the client to the server and vice versa, for enhanced ordered processing.

- Spring Framework makes configuration and wiring of Rabbit Qeues trivial, and takes apart a lot of complexity with the Dependency Injections, and pre-built template configurations. 

- This middle layer, can provide efficient and synchronous processing of app transactions. 


# References: 

Spring Guides - https://spring.io/guides/gs/messaging-rabbitmq/

Baeldung.com - https://www.baeldung.com/spring-amqp

## Instructions on how to run the app, 

### Please review the make file for commands:

### Basic Steps: 

-> Build (Gradle), Run (Gradle / BootRun) 

-> Docker : Build (Gradle), Build (Docker Image), Create Docker Network Bridge for RabbitMQ, Run (Docker Image)

