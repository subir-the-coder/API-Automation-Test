# API Automation Test

This repository contains **API Test Automation** implemented using **Postman collections** and executed via **Postman CLI (Newman)** with **GitHub Actions** for continuous integration.

It is primarily built to complete Postman API Test Automation assignments and demonstrate:

* Writing automated API tests in Postman
* Running collections via CLI
* Integrating API tests with GitHub Actions
* CI validation for multiple assignments

---

## 🚀 Features

* ✅ Automated API test cases using **Postman test scripts**
* ✅ CLI execution using **Postman CLI / Newman**
* ✅ CI/CD integration using **GitHub Actions**
* ✅ Supports environment variables and API keys
* ✅ Designed to meet **Postman badge & assignment evaluation criteria**

---

## 🧪 Tools & Technologies

* **Postman** – API testing & scripting
* **Postman CLI (Newman)** – Command‑line execution
* **GitHub Actions** – Continuous Integration
* **YAML** – Workflow configuration
* **REST APIs** – Test targets

---

## ⚙️ GitHub Actions Workflow

The workflow is located at:

```
.github/workflows/postman.yml
```

### What it does:

* Triggers on `push` and `pull_request`
* Installs Postman CLI
* Runs the Postman collection(s)
* Injects required environment variables (API keys, UUIDs, etc.)

---

## 🔐 Secrets & Environment Variables

Sensitive values are **never hardcoded**.

They are stored securely using **GitHub Secrets**, such as:

* `POSTMAN_API_KEY`
* `apiKey`
* `collection_uuid`

You can configure them in:

```
GitHub Repo → Settings → Secrets and variables → Actions
```

---

## 🏃 How to Run Locally

### Prerequisites

* Node.js
* Postman CLI or Newman

### Install Newman

```bash
npm install -g newman
```

### Run a Collection

```bash
newman run collections/Assignment-1.json
```

Or using Postman CLI:

```bash
postman collection run collections/Assignment-1.json
```

---

## 📌 Purpose of This Repository

This repository is created for:

* 📘 Learning API test automation
* 🎯 Completing Postman assignments
* 🏆 Claiming Postman badges
* 🧠 Understanding CI‑based API testing workflows

---

## 👤 Author

**Subir Sutradhar**
🔗 GitHub: [https://github.com/subir-the-coder](https://github.com/subir-the-coder)

---

## 📄 License

This project is for **educational and learning purposes**.

---

⭐ If you find this useful, feel free to star the repository!
