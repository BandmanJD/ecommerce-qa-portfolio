# API Test Scenarios

## Overview

This document identifies the high-level API functionality that will be validated for the E-Commerce QA Portfolio.

Test scenarios define **what** should be tested before detailed test cases are written. They help ensure complete test coverage and provide a roadmap for API validation.

---

## Products

| Scenario ID | Endpoint | Scenario | Priority |
|--------------|----------|----------|----------|
| API_SC_001 | GET /products | Retrieve all products | High |
| API_SC_002 | GET /products/{id} | Retrieve a product using a valid product ID | High |
| API_SC_003 | GET /products/{id} | Retrieve a product using an invalid product ID | High |
| API_SC_004 | GET /products | Verify the response is returned in JSON format | High |
| API_SC_005 | GET /products | Verify all required product fields are present | High |
| API_SC_006 | GET /products | Verify response time meets performance expectations | Medium |

---

## Authentication

| Scenario ID | Endpoint | Scenario | Priority |
|--------------|----------|----------|----------|
| API_SC_007 | POST /auth/login | Login using valid credentials | High |
| API_SC_008 | POST /auth/login | Login using an invalid username | High |
| API_SC_009 | POST /auth/login | Login using an invalid password | High |
| API_SC_010 | POST /auth/login | Login with missing required fields | High |

---

## Shopping Cart

| Scenario ID | Endpoint | Scenario | Priority |
|--------------|----------|----------|----------|
| API_SC_011 | GET /carts | Retrieve all shopping carts | Medium |
| API_SC_012 | POST /carts | Create a new shopping cart | High |
| API_SC_013 | DELETE /carts/{id} | Delete an existing shopping cart | Medium |

---

## Notes

The scenarios listed above identify the API functionality that will be validated throughout this portfolio. Detailed test cases, Postman requests, automated assertions, and execution results will be developed from these scenarios.
