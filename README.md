# 🚀 Node.js CI/CD Demo Project

A simple Node.js application demonstrating a basic CI/CD pipeline using GitHub Actions and Docker.

This project is built to understand core DevOps concepts:

- Version Control with Git
- Continuous Integration (CI)
- Docker containerization
- Automated builds using GitHub Actions

---

## 📌 Project Overview

This application runs a simple HTTP server that returns:

Hello DevOps World 🚀

The CI pipeline automatically:

- Checks out the code
- Installs dependencies
- Runs tests
- Builds a Docker image

The pipeline runs on every push to the `main` branch.

---

## 🛠️ Tech Stack

- Node.js
- Docker
- GitHub Actions

---

nodejs-cicd-demo/
│
├── app.js
├── package.json
├── Dockerfile
├── .gitignore
└── .github/
└── workflows/
└── ci.yml


---

## 📁 Project Structure
