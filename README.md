# Postman CI Workflow

This repository demonstrates a CI workflow for API testing using Postman and Newman CLI. It’s designed for scalable automation and easy integration with CI/CD pipelines like Jenkins or GitHub Actions.

---

## Features

-  Newman CLI integration for automated API testing
-  Data-driven testing using CSV files
-  Mock server setup for isolated test environments
-  CI/CD ready structure for Jenkins or GitHub Actions
-  Shell script automation for test execution

---

## Folder Structure


---

## How to Run Locally

```bash
newman run collections/api-tests.postman_collection.json \
  -e environments/staging.postman_environment.json \
  -d data/test-data.csv

---
CI/CD Integration
This setup is optimized for:

Jenkins: Add run-tests.sh as a build step

GitHub Actions: Use Newman CLI in workflow .yml files

Docker (optional): Containerize Newman for isolated test runs

Author
Dhirendra Kumar Backend Developer | Go | API Automation, Madhubani, Bihar , GitHub • LinkedIn


Feedback & Contributions
Feel free to fork, raise issues, or suggest improvements. Let’s build better APIs together! 🚀


</details>

---

## Step 3: Save and Exit

- Press `Ctrl + O` → then `Enter` to save
- Press `Ctrl + X` to exit

---

##  Step 4: Push to GitHub

```bash
git add README.md
git commit -m "Add README for Postman CI workflow"
git push
