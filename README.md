# SumergeTask
Explanation of Tests:
testElementsPresent: Verifies the presence of username, password fields, and the login button on the main screen.
testValidLogin: Tests a successful login with valid credentials and checks if the "Swag Labs" div is visible.
testInvalidLogin: Tests an unsuccessful login with invalid credentials and verifies the presence of the error message.
testEmptyUsername: Tests login with an empty username and verifies the specific error message.
testEmptyPassword: Tests login with an empty password and verifies the specific error message.
Running the Tests:
Ensure your ChromeDriver path is correctly set in the setup method. Then, you can run these tests using your IDE or from the command line with Maven: 'mvn test'
