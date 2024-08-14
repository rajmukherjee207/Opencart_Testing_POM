# Automated Account Registration Test
Overview

This project contains an automated test suite for account registration on an e-commerce website using Selenium WebDriver and TestNG. It demonstrates the use of page object model design patterns and utility methods for generating random data.
## Prerequisites

Before running the tests, ensure you have the following installed:

- **Java**: [Download and install Java](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- **Maven**: [Download and install Maven](https://maven.apache.org/download.cgi)
- **ChromeDriver**: [Download ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads) and place it in a directory included in your PATH.

## Project Structure
pageObjects/: Contains page classes with locators and methods for interacting with the web elements.
AccountRegistrationPage.java: Page object for the account registration page.
HomePage.java: Page object for the home page.
testBase/: Contains the base class for setting up and tearing down the test environment.
BaseClass.java: Initializes WebDriver, sets up the browser, and provides utility methods for generating random data.
testCases/: Contains test cases for the project.
TC_001_AccountRegistrationTest.java: Test case for verifying account registration functionality.

Setup

    Clone the repository:

    bash

git clone https://github.com/your-username/your-repository.git

Navigate to the project directory:

bash

cd your-repository

Features

Automated account registration with random data generation.
Validation of successful account creation with assertion of confirmation message.

'''
/your-repository
│
├── /src
│   ├── /test
│   │   ├── /java
│   │   │   └── /pageObjects
│   │   │       ├── AccountRegistrationPage.java
│   │   │       └── HomePage.java
│   │   │       └── BaseClass.java
│   │   │   └── /testBase
│   │   │       └── BaseClass.java
│   │   │   └── /testCases
│   │   │       └── TC_001_AccountRegistrationTest.java
│   │   │   └── /utility
│   │
│   ├── /resources
│
├── /target
│
├── pom.xml
└── README.md

'''
