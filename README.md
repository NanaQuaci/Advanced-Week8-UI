### 📊 CI Status


🧪 UI Automation Testing – Swag Labs Web App
This project demonstrates UI automation testing using Selenium WebDriver with the Page Object Model (POM) design pattern. It includes automation for core user flows such as Login and Cart functionality, and integrates with Allure Reports for detailed result visualization.

![UI Tests](https://github.com/NanaQuaci/Advanced-Week8-UI/actions/workflows/run-tests.yml/badge.svg)

🚀 Technologies Used
- **Java 21**
- **Selenium WebDriver – UI automation framework**
- **JUnit 5 – Test framework**
- **Allure – Report generation**
- **Maven – Build and dependency management**
- **Git & GitHub – Version control**

🧩 Project Structure
SwaglabsUIAutomation/
├── src
│   ├── main
│   │   └── java
│   │       └── com.example
│   │           ├── base         # BasePage class
│   │           └── pages        # Page classes (LoginPage, CartPage)
│   └── test
│       └── java
│           └── com.example
│               ├── base         # BaseTest class
│               ├── testdata     # Test data constants
│               └── tests        # LoginTest, CartTest
├── allure-results              # Allure test result outputs
├── pom.xml                     # Maven dependencies and plugins
└── README.md


✅ Test Coverage
🔐 Login Feature
- Valid login with correct credentials
- Invalid login with:
- Wrong username
- Wrong password
- Empty fields
- Username only
- Password only

🛒 Cart Feature
- Add item to cart
- Remove item from cart
- Verify cart badge updates
- Remove item without visiting cart page
- Checkout button visibility

📄 How to Run Tests
- Make sure you have Java 21, Maven, and Allure CLI installed.
# Clean and run all tests
mvn clean test

📊 How to Generate Allure Report
# Serve the report locally
allure serve allure-results

If you don’t have Allure installed: [Install Allure CLI](https://allurereport.org/docs/#_installing_a_commandline)

Allure Report Online
(Deployed to GitHub Pages)

### 🌐 View Deployed Report (CI)
➡️ [Allure Report (GitHub Pages)](https://nanaquaci.github.io/Advanced-Week8-UI/)

🔗 Useful Links
- Swag Labs Demo Site
- Selenium WebDriver Docs
- Allure Documentation
- JUnit

 
👤 Author
Nana Quaci

    Week 8 Lab Activity – Advanced Testing
    Graduate Trainee Program

🏁 License
This project is for educational and demonstration purposes only.