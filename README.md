# mailtravel_Automation
# Cucumber Automation Framework for Mailtravel

## Overview
This repository contains a Cucumber-based automation framework for testing Mailtravel. The framework is designed to provide a structured and maintainable way to write and execute automated tests using Cucumber and Selenium.

## Features
- **Cucumber:** Utilizes the Cucumber framework for writing behavior-driven tests.
- **Selenium:** Integrates Selenium for web automation.
- **Page Object Model (POM):** Follows the POM design pattern for better code organization and maintenance.
- **Reporting:** Generates detailed test reports for better visibility of test execution results.

## Prerequisites
- Java 17 or higher
- Maven 3.8.8
- ChromeDriver (or WebDriver for your preferred browser)

## Getting Started
1. Clone this repository to your local machine.
2. Install the necessary dependencies by running:
    ```bash
    mvn clean install
    ```
3. Run the tests using the following command:
    ```bash
    mvn test
    ```

## Folder Structure
- **src/main/java:** Contains the core framework code.
- **src/main/resources:** Includes configuration files,Cucumber feature files and step definitions and chromedriver.
- **src/test/java:** Contains the testcase runner code.

## Configuration
Update the `src/main/resources/ObjectRepository` file with your test details, such as the application URL, xpath path of objects, etc.  

## Reporting
Test reports are generated in the `target/cucumber-reports` directory after each test run.

## Contributing
Feel free to contribute to the development of this framework. Fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
