# REST API Testing Suite

A practical API testing project using **Postman and JavaScript** to validate REST API functionality, HTTP responses, JSON data structures, and error handling.

**API Under Test:** [JSONPlaceholder](https://jsonplaceholder.typicode.com/)

## Test Results

| Metric | Result |
|---|---|
| API Test Scenarios | 10 |
| Automated Assertions | 28 |
| Passed | 28 |
| Failed | 0 |
| HTTP Methods Tested | GET, POST, PUT, PATCH, DELETE |

All 10 requests passed during the Postman Collection Runner execution.

## Test Coverage

| Test ID | Scenario | Method |
|---|---|---|
| API-001 | Retrieve All Posts | GET |
| API-002 | Retrieve Single Post | GET |
| API-003 | Retrieve Nonexistent Post | GET |
| API-004 | Filter Posts by User ID | GET |
| API-005 | Create New Post | POST |
| API-006 | Update Existing Post | PUT |
| API-007 | Partially Update Post | PATCH |
| API-008 | Delete Post | DELETE |
| API-009 | Validate Response Structure | GET |
| API-010 | Validate Response Time | GET |

## Testing Techniques

- HTTP status code validation
- Positive and negative API testing
- JSON response structure and data type validation
- Request and response body verification
- Query parameter testing
- CRUD operation response validation
- Response time assertions
- Automated JavaScript assertions using Postman

**Note:** JSONPlaceholder simulates POST, PUT, PATCH, and DELETE operations. Successful responses do not indicate persistent database changes.

## Tools

- Postman
- JavaScript
- REST APIs
- JSON
- Git & GitHub

## Running the Tests

1. Download the [Postman collection](collection/REST_API_QA_Testing_Suite.postman_collection.json).
2. Import the JSON file into Postman.
3. Open the **REST API QA Testing Suite** collection.
4. Select **Run** to open the Collection Runner.
5. Execute all 10 requests.
6. Review the automated assertion results.

No API authentication is required.

## Execution Evidence

![Postman Collection Runner Results](evidence/collection_run.png)

## About This Project

This project was created independently as part of my software quality assurance portfolio to demonstrate practical REST API testing, JavaScript assertions, and test execution using Postman.

**GitHub Portfolio:** [github.com/troy-duheme](https://github.com/troy-duheme)