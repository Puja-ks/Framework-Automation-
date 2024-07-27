**Introduction**

This project is an automated testing framework designed for an e-commerce web application.  
The framework utilizes Selenium for web automation, Java for scripting test cases, TestNG for test management, Page Object Model (POM) for structuring tests, and Extent Reports for detailed test reporting.

**Technologies Used**

**Selenium:** Web automation tool used for UI testing.

**Java:** Programming language used for writing test scripts.

**TestNG:** Testing framework for managing test cases.

**Page Object Model (POM)**: Design pattern for creating object repositories for web UI elements.

**Extent Reports**: Library for generating detailed and interactive test reports.

**Prerequisites**

Java Development Kit (JDK)

Apache Maven

Selenium WebDriver

TestNG

Extent Reports

IDE (e.g., IntelliJ IDEA, Eclipse)

Jenkins (for CI integration)


**Setup and Installation**

1.Clone the Repository

**git clone https://github.com/your-username/Framework-Automation.git
**
2.Install Dependencies

Ensure you have Apache Maven installed. 
Run the following command to install all necessary dependencies:

**mvn clean install**

3.Configure WebDriver
Download the appropriate WebDriver for your browser (e.g., ChromeDriver, GeckoDriver) and update the path in the configuration file.

4.Execute the test suite using Maven

**mvn test**

6.For generating Extent Reports, ensure the following configuration is present in the testng.xml file:

**<listeners>
    <listener class-name="com.aventstack.extentreports.testng.listener.ExtentITestListenerAdapter"/>
</listeners>**

