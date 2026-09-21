# 🧪 Restful Booker API Testing

> API automation testing project using **Postman** and **Newman**, with automated assertions and HTML test reporting.

---

## 📌 Project Overview

This project demonstrates API testing of the **Restful Booker API** using a Postman collection and environment.

The collection contains API requests, test scripts, assertions, and environment variables. The tests can be executed manually in Postman or automatically from the command line using Newman.

---

## 🛠️ Tools & Technologies

- **Postman** — API development and testing
- **Newman** — Command-line API test execution
- **JavaScript** — Test scripts and assertions
- **JSON** — Collection and environment configuration
- **HTML** — Automated test reports

---

## 📂 Project Structure

```text
API_Testing_RestfulBooker/
│
├── CollectionforAPI.postman_collection.json
├── EnvironmentforAPI.postman_environment.json
├── API_Report_newman.html
├── newmanReport.png
└── README.md
```

### 📄 File Description

| File | Purpose |
|---|---|
| `CollectionforAPI.postman_collection.json` | Postman collection containing API requests, scripts, and assertions |
| `EnvironmentforAPI.postman_environment.json` | Environment variables required for API testing |
| `API_Report_newman.html` | HTML report generated after Newman execution |
| `newmanReport.png` | Screenshot of the Newman test report |

---

## 🔍 Testing Scope

The project covers:

- ✅ API request validation
- ✅ HTTP status code validation
- ✅ Response body validation
- ✅ JSON data validation
- ✅ Test script execution
- ✅ Assertions
- ✅ Environment variable handling
- ✅ Automated collection execution
- ✅ Newman HTML reporting

---

## ▶️ Run the Project in Postman

### 1. Import the Collection

Open Postman and import:

```text
CollectionforAPI.postman_collection.json
```

### 2. Import the Environment

Import:

```text
EnvironmentforAPI.postman_environment.json
```

### 3. Select the Environment

Select the imported environment from the environment selector in Postman.

### 4. Run the Collection

1. Open the collection.
2. Click **Run**.
3. Select the required requests.
4. Click **Run Collection**.
5. Review the response and test results.

---

## ⚡ Run with Newman

### Install Newman

Make sure Node.js is installed, then run:

```bash
npm install -g newman
```

### Execute the Collection

Run the collection with the environment:

```bash
newman run CollectionforAPI.postman_collection.json -e EnvironmentforAPI.postman_environment.json
```

---

## 📊 Generate an HTML Report

Use Newman with the HTML Extra reporter:

```bash
newman run CollectionforAPI.postman_collection.json -e EnvironmentforAPI.postman_environment.json -r htmlextra --reporter-htmlextra-export API_Report_newman.html
```

After execution, open:

```text
API_Report_newman.html
```

in a web browser to review the test results.

---

## 📈 Test Reporting

The project provides an HTML report containing the Newman execution results.

**Report:** `API_Report_newman.html`

**Report Screenshot:** `newmanReport.png`

---

## 🚀 Key Features

- 🔹 Reusable Postman collection
- 🔹 Environment-based variable management
- 🔹 Automated API assertions
- 🔹 Command-line execution with Newman
- 🔹 HTML test reporting
- 🔹 Easy integration with GitHub

---

## 👤 Author

**Tasmin Jannat Tahsin**
