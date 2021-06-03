# Contract Testing With Pact
This tutorial will walk through writing a contract test between the [React](https://reactjs.org/) 
frontend and the [Spring Boot](https://spring.io/projects/spring-boot) REST API.  The contract testing
framework that we will use is [Pact](https://pact.io).

## The Problem
When you stand up two or more systems that talk to each other integration testing gets very complicated in 
the real world.
- All systems have to be running
- All down stream dependencies like database also have to be running
- Tests must have security credentials to run the consuming systems

And the list goes on.  As the number of connected systems grows the testing complexity grows exponentially.
Contract Testing decouples these systems and tests both sides of their interactions.  This drastically
simplifies testing and increases the speed of testing.  For a short and powerful illustration visit 
https://pactflow.io/how-pact-works.

## Prerequisites
- Free [PactFlow](https://pactflow.io) account
