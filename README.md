## This is a simple Python project that includes automated testing and CI/CD using GitHub Actions.

## 🚀 Features
- ✅ Runs automated tests using `pytest`
- ✅ Uses GitHub Actions to check code automatically
- ✅ Manages dependencies with `requirements.txt`

## 📂 Project Structure
```
📦 Project
├── 📂 src          # Main code files
├── 📂 tests        # Test scripts
├── 📄 requirements.txt  # List of required libraries
├── 📄 .github/workflows/python-app.yml  # GitHub Actions setup
└── 📄 README.md    # This file (documentation)
```

## ⚙️ How to Set Up and Run
### Requirements
- Python 3.8 or newer
- `pip` installed (comes with Python)

### Install Required Libraries
```bash
pip install -r requirements.txt
```

### Run Tests
```bash
pytest
```

## 🤖 GitHub Actions (Automated Checks)
This project uses **GitHub Actions** to automatically check the code when new changes are made.

### 📜 What Happens Automatically?
1. The workflow runs when code is pushed or a pull request is created for the `main` branch.
2. It runs on a cloud computer with Ubuntu.
3. It performs these steps:
   - Downloads the latest code
   - Sets up Python 3.8
   - Installs required libraries
   - Runs tests to check if the code is working

### Workflow File Location
The GitHub Actions setup is stored in:
```
.github/workflows/python-app.yml
```

## 💡 How to Contribute
1. **Fork** the repository (make a copy on your GitHub account)
2. **Create a new branch** (for example, `new-feature`)
3. **Make your changes** and commit them
4. **Push** your branch to GitHub
5. **Create a Pull Request** (ask to merge your changes)


