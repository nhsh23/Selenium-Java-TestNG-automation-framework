# Selenium Java Automation Framework

This is a lightweight and scalable **Selenium + Java + TestNG** automation framework, designed using the **Page Object Model** (POM) pattern. The project demonstrates login automation on the demo site [saucedemo.com](https://www.saucedemo.com).

---

## Tech Stack

- **Language**: Java  
- **Automation Tool**: Selenium WebDriver  
- **Build Tool**: Maven  
- **Test Framework**: TestNG  
- **Design Pattern**: Page Object Model (POM)  
- **Utilities**: WebDriverManager  
- **Reporting**: ExtentReports (optional integration)  

---

## Project Structure
selenium-java-framework/ │ ├── src/ │ ├── main/java/ │ │ ├── base/ # Base test setup (browser config) │ │ ├── pages/ # Page classes (POM) │ └── test/java/ │ └── tests/ # TestNG test classes │ ├── pom.xml # Maven dependencies ├── testng.xml # TestNG suite runner └── README.md # Project documentation


---

## How to Run

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/selenium-java-framework.git
   cd selenium-java-framework

**2. Install dependencies:**

mvn clean install

**3. Run Tests:**

mvn test

**Demo Site Used
Sauce Demo
Credentials:**

**Username:** standard_user

**Password:** secret_sauce










