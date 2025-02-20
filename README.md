# Magento Selenium TestNG Data-Driven Automation

🚀 Overview

Magento Selenium TestNG Data-Driven Automation is a test automation framework designed for end-to-end testing of a Magento eCommerce application. This project automates the complete flow of user authentication, product addition to the cart, and order placement.

✨ Features

*   Automated User Journey: Covers login, product selection, and order placement.
*   Data-Driven Testing: Uses external test data for multiple test cases.
*   Randomized Email Generation: Ensures unique logins with dynamically generated emails.
*   Random Product Selection: Simulates real user behavior by randomly choosing products.
*   Assertions for Validation: Uses assertions to verify expected results, ensuring test reliability.

🛠️ Technologies Used

*   Selenium WebDriver - Browser automation
*   TestNG - Test execution and reporting
*   Java - Programming language
*   Excel/CSV (Data-Driven Testing) - External data handling

📂 Project Structure
magento-selenium-testng-pom/
├── src/
│   ├── main/java/pages/        # Page classes
│   ├── main/java/utils/        # Utility functions
│   ├── test/java/tests/        # Test cases
│   ├── test/java/base/         # Base test class
│   ├── resources/              # Configuration files
├── pom.xml                     # Maven dependencies
├── testng.xml                  # TestNG test suite configuration

📥 Installation & Setup

**Prerequisites**

*   Install Java JDK 8+
*   Install Maven
*   Set up TestNG plugin in your IDE

**Steps to Setup**

1.  Clone the repository:
    ```bash
    git clone [https://github.com/rahmannazneen/Nazn33n-magent-selenium-testng-datadriven.git](https://github.com/rahmannazneen/Nazn33n-magent-selenium-testng-datadriven.git)
    ```
2.  Open the project in an IDE (e.g., IntelliJ IDEA, Eclipse).
3.  Install dependencies via Maven:
    ```bash
    mvn clean install
    ```
4.  Run the TestNG suite file.
5.  View the detailed test report.

🔎 Test Execution & Reporting

*   The tests are executed using TestNG.
*   Assertions ensure validation of expected results.
*   A detailed TestNG report is generated post-execution.

🤝 Contribution

Contributions are welcome! Feel free to fork this repository and improve test coverage, add new test cases, or optimize the framework.

📜 License

This project is open-source and available for public use.

👩‍💻 Author

rahmannazneen

Happy Testing! 🚀
