# SWT301
# Test Automation Readme

This repository contains automated test cases for the TechPanda website. The tests have been implemented using [Selenium](https://www.selenium.dev/) and [JUnit](https://junit.org/junit5/).

## Test Cases

### TC01: Verify Sorting Functionality

**Test Steps:**

1. Go to [TechPanda](http://live.techpanda.org/).
2. Verify the title of the page.
3. Click on the 'MOBILE' menu.
4. In the list of all mobiles, select 'SORT BY' dropdown as 'name'.
5. Verify that all products are sorted by name.

### TC02: Verify Product Cost Equality

**Test Steps:**

1. Go to [TechPanda](http://live.techpanda.org/).
2. Click on the 'MOBILE' menu.
3. In the list of all mobiles, read the cost of Sony Xperia mobile (which is $100).
4. Click on the Sony Xperia mobile.
5. Read the Sony Xperia mobile from the detail page.
6. Compare the product value in the list and detail page to ensure they are equal ($100).

## Setup

1. Install Java (JDK) - [Link to Java](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
2. Install Selenium WebDriver - [Link to Selenium](https://www.selenium.dev/downloads/)
3. Set up JUnit - [Link to JUnit](https://junit.org/junit5/)

## Running the Tests

1. Clone the repository: `git clone <repository_url>`
2. Navigate to the project directory.
3. Run the tests using the command `mvn test`.
4. View the test reports in the output directory.

## Contributors

- [Your Name](https://github.com/sontv6666)
- [Other Contributor](https://github.com/other_contributor)

Feel free to open an issue or submit a pull request for any improvements or suggestions.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
