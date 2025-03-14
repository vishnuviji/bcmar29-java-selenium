# Java Selenium E-Commerce Automation

This project is a Java-based automation framework for testing an e-commerce website using Selenium WebDriver and TestNG.

## Prerequisites

- Java 17
- Maven

## Project Structure

- `src/test/java/com/example/pages/`: Contains page object classes for different pages of the e-commerce website.
- `src/test/java/com/example/tests/`: Contains test classes for executing test cases.
- `pom.xml`: Maven configuration file with project dependencies and plugins.


## Setup

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd java-selenium
    ```

2. Install the dependencies:
    ```sh
    mvn clean install
    ```

3. Ensure ChromeDriver is installed and available in your system PATH.

## Running Tests

To run the tests, use the following Maven command:
```sh
mvn test