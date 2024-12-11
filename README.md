# AutomationOnJunit

## Project Summary
This project focuses on automating two web forms using **Selenium WebDriver** and **JUnit** to ensure proper functionality, field validation, and success message verification.
![ass2](https://github.com/user-attachments/assets/c17444e6-812b-4d0a-bbdc-89bfd6cda9de)

### Web Forms to Automate:
1. **Practice Web Form**: [Practice Webform for Learners](https://www.digitalunite.com/practice-webform-learners)
2. **Guest Registration Form**: [Guest Registration Form](https://demo.wpeverest.com/user-registration/guest-registration-form/)

## Requirements
Before you start, ensure that the following tools are installed:

- **Java Development Kit (JDK)** version 8 or later
- **Maven** for project management and dependency resolution
- **Selenium WebDriver** to automate browser actions
- **ChromeDriver** (or any other browser driver depending on your choice)
- **IDE** (such as IntelliJ IDEA, Eclipse) for writing and running tests

## Setup Instructions

1. **Install Browser Driver**:
   - Download the correct browser driver (e.g., **ChromeDriver**).
   - Make sure the driver is added to your system’s **PATH** for easy access.

2. **Project Setup**:
   - Clone or download the repository.
   - Open the project in your preferred IDE and let Maven download the dependencies.

## Automated Testing Workflow

### Testing the Practice Web Form
1. Visit the **Practice Webform for Learners** page: [Link to Form](https://www.digitalunite.com/practice-webform-learners).
2. Fill in all required form fields.
3. Upload a file (file size limit: 2MB).
4. Submit the form and ensure that it is successfully submitted.
5. Verify that the message **"Thank you for your submission!"** appears.

### Testing the Guest Registration Form
1. Visit the **Guest Registration Form** page: [Link to Form](https://demo.wpeverest.com/user-registration/guest-registration-form/).
2. Complete the form with the following fields:
   - First Name
   - Last Name
   - Email Address
   - Gender
   - Date of Birth
   - Nationality
   - Phone Number
   - Country (set to Bangladesh)
3. Agree to the **Terms & Conditions**.
4. Submit the form and check for successful registration.
5. Confirm that the registration success message is displayed.

## Running the Automation Tests

1. Open the project in your IDE.
2. Run the tests through **JUnit**.
3. Observe the automation in action as the browser opens, interacts with the form, and submits it. Check the console for logs and results.

## Troubleshooting Tips

- **Element Not Found**: If an element cannot be located, verify the element's locator (e.g., `id`, `name`, or `xpath`) and ensure that wait times are properly set.
- **Driver Compatibility**: Make sure that the version of your browser matches the version of the driver you are using (e.g., ChromeDriver with Google Chrome).
- **Validation Issues**: Check the input fields for valid data (e.g., proper email format, correct file size for uploads).
