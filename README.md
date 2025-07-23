# DevOps CI/CD Demo Project with Flask

## Description
This is a simple Flask-based web application designed to demonstrate CI/CD pipeline integration using GitHub Actions.

## How to Run

### Run locally
```bash
pip install -r requirements.txt
python app.py
```

### Run with Docker
```bash
docker build -t devops-flask-app .
docker run -p 5000:5000 devops-flask-app
```

Then open your browser and go to `http://localhost:5000`

## CI/CD with GitHub Actions
On every push to the `main` branch, the pipeline will:
- Checkout the code
- Install dependencies
- Simulate a test phase (you can add pytest or any test runner)

## Author
Prepared for university DevOps project presentation.
