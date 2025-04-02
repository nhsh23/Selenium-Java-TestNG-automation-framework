# 🚀 Selenium + Java Automation Framework

[![Java](https://img.shields.io/badge/Language-Java-blue.svg)](https://www.java.com)
[![Selenium](https://img.shields.io/badge/Framework-Selenium%20WebDriver-brightgreen)](https://www.selenium.dev)
[![TestNG](https://img.shields.io/badge/Test-Framework-TestNG-orange)](https://testng.org/)
[![Maven](https://img.shields.io/badge/Build-Maven-cc3c3c)](https://maven.apache.org/)

This project is a fully functional **Selenium + Java Automation Framework**, built from scratch using best practices and the Page Object Model (POM) design pattern.

> 📦 Ready to use! Download and run on your IDE in minutes.

---

## 📥 Download Framework

👉 
💡 After unzipping, import it into IntelliJ or Eclipse and run the test class.

---

## 💡 Features

- 🔹 Selenium WebDriver with Java
- 🔹 TestNG for test management
- 🔹 Page Object Model (POM)
- 🔹 WebDriverManager for effortless browser setup
- 🔹 Simple Login Test for [saucedemo.com](https://www.saucedemo.com)

---

## 🏗️ Project Structure

selenium-java-framework/
│
├── src/
│   ├── main/
│   │   └── java/
│   │       └── base/                 // WebDriver setup
│   │       └── pages/                // Page classes (POM)
│   │       └── utils/                // Utility classes
│   │       └── config/               // Configuration loader
│   └── test/
│       └── java/
│           └── tests/               // TestNG test classes
│
├── testng.xml
├── pom.xml
└── README.md / Readme_new.md


---

## 🔍 Test Scenario

```java
@Test
public void testValidLogin() {
    LoginPage loginPage = new LoginPage(driver);
    loginPage.login("standard_user", "secret_sauce");

    HomePage homePage = new HomePage(driver);
    Assert.assertEquals(homePage.getHeaderText(), "Products");
}


🖼️ **Framework Architecture**
Language: Java
Automation Tool: Selenium WebDriver
Build Tool: Maven
Test Framework: TestNG
Design Pattern: Page Object Model (POM)
Logging: Log4j
Reporting: ExtentReports
Utilities: WebDriverManager


👨‍💻** Author**
Neha Sharma
🔗 LinkedIn Profile https://www.linkedin.com/in/neha-sharma-0a0906148/  
💻 https://github.com/nhsh23

🏷️** Tags**
#Selenium #Java #Automation #TestNG #QAEngineer #PageObjectModel #WebDriverManager #OpenSource
