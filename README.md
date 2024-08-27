# Health Insurance System

## Overview
The Health Insurance System is a microservices-based project designed to manage and facilitate health insurance processes. The system is built using Spring Boot and provides RESTful APIs for various components of the insurance workflow.

## Microservices
The project consists of the following microservices:

1. **AR-API**: Handles application registrations and user accounts.
2. **CITIZEN-API**: Manages citizen information and profiles.
3. **CO-API**: Manages coordination between different organizations.
4. **DC-API**: Data collection and processing service.
5. **ED-API**: Handles eligibility determination processes.
6. **PLANS-API**: Manages insurance plans and their details.
7. **REPORTS-API**: Generates reports related to health insurance.

## Project Structure
Each microservice is encapsulated in its own module with the following structure:

## Prerequisites
- Java 17 or higher
- Spring Boot 3.x
- Docker
- MySQL
- RabbitMQ / Kafka (depending on message broker used)
