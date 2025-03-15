# Python Application with CI/CD

This repository contains a simple Python project with basic mathematical operations and automated testing using **GitHub Actions**.

## Project Overview
This project demonstrates:
- Writing Python functions for basic math operations
- Testing with **pytest**
- Setting up a **CI/CD workflow** using **GitHub Actions**

## Folder Structure
```
/
├── src/
│   ├── math_operations.py  # Contains add and sub functions
├── test_math_operations.py # Unit tests for math operations
├── .github/workflows/
│   ├── ci-cd.yml           # GitHub Actions workflow
└── README.md               # Project documentation
```

## Setup and Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Git

### Clone the Repository
```sh
git clone https://github.com/Brahme27/your-repository.git
cd your-repository
```

### Install Dependencies
```sh
pip install -r requirements.txt
```

### Run the Python Script
If you have a `main.py` file, run it as:
```sh
python main.py
```

## Running Tests
To run unit tests using **pytest**:
```sh
pytest
```

## CI/CD Pipeline with GitHub Actions
This repository is configured with a **CI/CD workflow** that automates the following steps:
1. **Build and Test** - On every push or pull request to `main`:
   - Checkout the code
   - Set up Python and install dependencies
   - Run tests using pytest

### Workflow File (`.github/workflows/ci-cd.yml`)
```yaml
on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main
```

