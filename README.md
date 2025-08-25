# Account Service

## Description
Manages bank accounts and balances linked to users.

## Technologies
- Java 17
- Spring Boot
- Spring Data JPA
- PostgreSQL
- Maven

## Features
- Create, update, delete accounts
- Fetch account details
- Manage balance per user

## Endpoints
- `POST /accounts` → Create account
- `GET /accounts/{id}` → Get account details
- `PUT /accounts/{id}` → Update account
- `DELETE /accounts/{id}` → Delete account

## Database Schema
- **accounts**
    - id: UUID
    - userId: UUID
    - accountNumber: String
    - balance: Decimal
