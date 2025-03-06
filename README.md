# Postman_-2_RestfullBooker_APIProject
🚀 API Testing for RESTful Booker | A comprehensive test suite using Postman, Newman, and AI-generated test scripts to validate the functionality, security, and performance of the RESTful Booker API. Includes detailed test reports, test cases, and execution results for ensuring API reliability.  Let me know if you want any modifications! 🚀
# RESTful Booker API Testing

## 📌 Project Overview
This project aims to test the **RESTful Booker API**, a fictional hotel booking system, ensuring its functionality, reliability, security, and performance through automated API testing.

## 🛠️ Technologies Used
- **Postman** - API testing & collection creation (with AI-generated test scripts)
- **Newman** - CLI tool for running Postman collections
- **HTML Reports** - Test execution results visualization

## 📂 Folder Structure
```
📦 RESTful-Booker-API-Testing
 ┣ 📂 Postman_Collections   # Contains Postman JSON collection
 ┣ 📂 Reports               # Newman HTML reports
 ┣ 📂 Documentation         # Test Plan, Test Cases, Summary
 ┣ 📜 README.md             # Project Overview & Setup Instructions
```

## 🚀 How to Run Tests
### 1️⃣ Install Dependencies
Ensure **Node.js** and **Newman** are installed:
```sh
npm install -g newman
npm install -g newman-reporter-htmlextra
```

### 2️⃣ Run Postman Collection
Execute tests via **Newman**:
```sh
newman run Postman_Collections/#2Project_Restfull_Booker.postman_collection.json -r cli,htmlextra --reporter-htmlextra-export Reports/newman-report.html
```

## 📊 Test Results & Reports
- **Test Execution Report:** [newman-report.html](newman-report.html)
- **Test Plan :** "restful-booker_Test Plan.pdf"

![image](https://github.com/user-attachments/assets/65df28b6-34fb-41cc-afe5-e813653850ef)

