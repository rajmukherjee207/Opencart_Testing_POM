# OpenCart Testing POM

This repository contains test automation scripts for OpenCart using the Page Object Model (POM) design pattern. The tests are implemented using Selenium WebDriver.

## Prerequisites

Before running the tests, ensure you have the following installed:

- **Java**: [Download and install Java](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- **Maven**: [Download and install Maven](https://maven.apache.org/download.cgi)
- **ChromeDriver**: [Download ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads) and place it in a directory included in your PATH.

## Project Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/rajmukherjee207/Opencart_Testing_POM.git
   cd Opencart_Testing_POM
'''

Install Dependencies:

    Navigate to the project directory and run:

    bash

        mvn install

Running Tests

    Navigate to the Project Directory:

    bash

cd Opencart_Testing_POM

Run the Tests:

    To execute the test cases, use Maven:

    bash
        mvn test

Basic Login Test

The LoginTest class contains a simple test for logging into an OpenCart application. Here is a brief overview of the test:

    Navigate to the Login Page:
    The test opens the OpenCart login page.

    Enter Credentials:
    The test fills in the username and password fields.

    Submit Login Form:
    The test clicks the login button.

    Verify Login:
    The test checks if the login was successful by verifying the presence of an element that appears only after a successful login.
