# 🧪 Cypress QA Project

This repository contains automated **API** and **UI** test cases built using **Cypress**.  
It helps verify both backend API responses and frontend user interactions efficiently.

---

## 📂 Project Structure
```
cypress-dev-qa/
│
├── API-testing/      # Contains API test cases
├── UI-testing/       # Contains UI test cases
└── README.md
```

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
   ```

2. **Navigate to the Project Directory**
   ```bash
   cd cypress-dev-qa
   ```

3. **Install Dependencies**
   ```bash
   npm install
   ```

4. **Run Tests in Cypress Test Runner**
   ```bash
   npx cypress open
   ```

5. **Run Tests in Headless Mode**
   ```bash
   npx cypress run
   ```

---

## 🧾 Example Tests
- ✅ Validate API response status and data  
- ✅ Verify login and navigation flow  
- ✅ Test form submissions and error messages  
- ✅ End-to-end UI and API integration checks  

---

## 💡 Best Practices
- Keep tests independent and modular  
- Use fixtures for test data  
- Reuse custom commands in `cypress/support/commands.js`  
- Maintain clean folder structure for scalability  

