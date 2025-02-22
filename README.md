# Spring_user_management

## Identity Authorization Service
A REST API for User and Role management, token generation and validation

## Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Data Seed](#data-seed)
- [Deployment](#deployment)
- [Tests](#tests)


## Features
This features are available in this service

- **User Registration:** Register user and send email for confirmation
- **Password reset: Send email with a reset link**
- **Authentication with JWT:** Generate JWT Access token and a random string for Refresh token the login
- **Logger:** Log info/error message into a log file
- **Role based authorization:** Allow or denied access to a resource according to user's role
- **Swagger:** API Documented with Swagger 2
- **HTML Email:** Use Thymeleaf to build HTML templates for email
