# Postman CI Workflow

This repository demonstrates a CI workflow for API testing using Postman and Newman CLI. It’s designed for scalable automation and easy integration with CI/CD pipelines like Jenkins or GitHub Actions.

---

## Features

-  Newman CLI integration for automated API testing
-  Data-driven testing using CSV files
-  Mock server setup for isolated test environments
-  CI/CD ready structure for Jenkins or GitHub Actions
-  Shell script automation for test execution



## How to Run Locally

```bash
newman run collections/api-tests.postman_collection.json \
  -e environments/staging.postman_environment.json \
  -d data/test-data.csv


Author
Dhirendra Kumar Backend Developer | Go | API Automation, Madhubani, Bihar , GitHub • LinkedIn




