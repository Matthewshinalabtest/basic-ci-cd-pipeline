# Basic CI/CD Pipeline with GitHub Actions

## Project Overview

This project demonstrates a basic CI/CD pipeline using GitHub Actions to automate the testing of a simple Python application. The pipeline runs tests automatically when code is pushed to the repository or when a pull request is created.

## Project Structure

- `app.py`: Contains a simple function to add two numbers.
- `test_app.py`: Contains tests for the `add` function using pytest.
- `.github/workflows/ci.yml`: GitHub Actions workflow file that defines the CI process.

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/basic-ci-cd-pipeline.git
   cd basic-ci-cd-pipeline