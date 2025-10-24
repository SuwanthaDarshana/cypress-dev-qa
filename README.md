# 🧪 Cypress QA Project

This repository contains automated **API** and **UI** test cases built using **Cypress**.  
It helps verify both backend API responses and frontend user interactions efficiently.

---

## 📂 Project Structure
cypress-dev-qa/
│
├── API-testing/ # Contains API test cases
├── UI-testing/ # Contains UI test cases
└── README.md

yaml
Copy code

---

## ⚙️ Tools Used
- **Cypress** – for UI and API testing  
- **JavaScript** – scripting language  
- **Node.js + npm** – runtime and dependency management  

---

## 🚀 How to Run Tests

1. **Clone the Repository**
   ```bash
   git clone https://github.com/SuwanthaDarshana/cypress-dev-qa.git
Navigate to the Project Directory

bash
Copy code
cd cypress-dev-qa
Install Dependencies

bash
Copy code
npm install
Run Tests in Cypress Test Runner

bash
Copy code
npx cypress open
Run Tests in Headless Mode

bash
Copy code
npx cypress run
🧾 Example Tests
✅ Validate API response status and data

✅ Verify login and navigation flow

✅ Test form submissions and error messages

✅ End-to-end UI and API integration checks

💡 Best Practices
Keep tests independent and modular

Use fixtures for test data

Reuse custom commands in cypress/support/commands.js

Maintain clean folder structure for scalability
