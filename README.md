# API-project-Crud
# Postman CRUD API Testing Project

## 📌 Project Overview
This project demonstrates API testing using **Postman** for performing **CRUD operations** (Create, Read, Update, Delete) on REST APIs.  
It covers request validation, authentication handling, data-driven testing, and automated execution using the Postman Collection Runner.

---

## 🛠️ Tools & Technologies Used
- Postman
- REST API
- JSON
- CSV (for data-driven testing)
- GitHub (version control)

---

## 🔐 Authentication
- Token-based authentication is implemented.
- Token is generated from the **Login API** and stored as an environment variable.
- The token is reused across all secured APIs using the `Authorization` header.


---

## 🔄 APIs Covered

### ✅ CREATE
- Method: `POST`
- Description: Create a new resource
- Validations:
  - Status code
  - Response body fields
  - Response time

### ✅ READ
- Method: `GET`
- Description: Retrieve resource details
- Validations:
  - Status code
  - Correct data retrieval

### ✅ UPDATE
- Method: `PUT / PATCH`
- Description: Update existing resource
- Validations:
  - Updated values
  - Status code

### ✅ DELETE
- Method: `DELETE`
- Description: Remove resource
- Validations:
  - Successful deletion
  - Resource not found on re-fetch

---

## 📊 Data-Driven Testing
- CSV file is used to run the same API with multiple data sets.
- Collection Runner is used for execution.
- Variables are dynamically replaced using `{{variableName}}`.

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/postman-api-project.git
   Create own environment and variables 

## 📂 Project Structure
