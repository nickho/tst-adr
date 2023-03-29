# Create a connexion between Tiger and Wolf

* Status: proposed
* Date: 2023-03-29

## Context and Problem Statement

We faced the need to connect the application Tiger to the application Wolf for sending messages

## Considered Options

* Connect using RabbitMQ
* Connect using REST API

## Decision Outcome

Chosen option: "Connect using RabbitMQ", because It provides loose coupling between the 2 applications
