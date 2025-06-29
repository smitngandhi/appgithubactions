# 🔪 Python CI with GitHub Actions

This is my first GitHub Actions project that demonstrates Continuous Integration (CI) with automated testing using `pytest`.

---

## 📁 Project Structure

```
.
├── .github/
│   └── workflows/
│       └── main.yml       # CI workflow
├── src/
    └── __init__.py # for importing
│   └── math_operations.py # Sample math operations
├── tests/
    └── __init__.py # for importing
│   └── test_operations.py # Unit tests for math operations
├── requirements.txt       # Dependencies
└── README.md              # Project overview
```

---

## 🚀 What This Project Does

1. Defines basic math operations inside `src/math_operations.py`.
2. Adds test cases using `pytest` in `tests/test_operations.py`.
3. Automates testing with **GitHub Actions** whenever code is pushed or a pull request is made to the `main` branch.

---

## ⚙️ GitHub Actions Workflow

The workflow defined in `.github/workflows/main.yml` performs the following steps:

* ✅ Checks out the code
* 🐍 Sets up Python 3.12.7
* 📆 Installs dependencies from `requirements.txt`
* 🧪 Runs tests using `pytest`

---

## 🧪 Run Locally

To test locally before pushing:

```bash
pip install -r requirements.txt
pytest
```

---

## 💡 Tech Stack

* Python
* pytest
* GitHub Actions

---

## ✅ Status

This project is up and running with basic CI. Future enhancements might include linting, coverage reporting, and deployment automation.

---

Feel free to fork and build upon this!
