# API Test Plan 

## Project

E-Commerce QA Portfolio - API Testing

---

## Objective

The objective of this test plan is to validate the functionality, reliability, and performance of the e-commerce REST API. Testing focuses on verifying that API endpoints return the correct status codes, response bodies, response times, and error handling for both valid and invalid requests.

---

## Scope

The following API modules will be tested:

- Products
- Authentication
- Shopping Cart

---

## API Endpoints

### Products

- GET /products
- GET /products/{id}

### Authentication

- POST /auth/login

### Shopping Cart

- GET /carts
- POST /carts
- DELETE /carts/{id}

---

## Test Types

- Functional Testing
- Positive Testing
- Negative Testing
- Response Validation
- Status Code Validation
- Performance Validation
- Regression Testing

---

## Test Environment

Tool:
- Postman

API Type:
- REST API

Response Format:
- JSON

Version Control:
- GitHub

---

## Entry Criteria

- API endpoints are available
- Test environment is configured
- Postman collection created

---

## Exit Criteria

Testing is complete when:

- All planned test cases have been executed
- Critical defects are resolved
- Test execution report is completed

---

## Deliverables

- API Test Plan
- Test Scenarios
- Test Cases
- Postman Collection
- Bug Reports
- Test Execution Report
- Newman Report

---

## Risks

- API downtime
- Network connectivity issues
- Invalid test data
- Third-party API limitations
