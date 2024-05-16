# SapphireLoginTC
Valid and invalid test cases for Sapphire login screen
# Sapphire Login Screen Test Suite

This repository contains test cases to validate the login screen of the Sapphire application.

# Test Cases

## Valid Test Cases

### Test Case 1: Successful Login
**Description:** Verify that a user can successfully login with valid credentials.
**Steps:**
  1. Open the Sapphire login page.
  2. Enter a valid username and password.
  3. Click the login button.
**Expected Result:** The user should be logged in successfully and directed to the campaign dashboard.

#### Test Case 2: Remember Me Functionality
**Description:** Verify that the page title of login screen.
**Steps:**
  1. Open the Sapphire login page.
  2. Check the page title.
  **Expected Result:** After logging out and revisiting the login page, the page title should be displayed as expected.

## Invalid Test Cases

### Test Case 3: Invalid Username
**Description:** Verify that the user cannot login with an invalid username.
**Steps:**
  1. Open the Sapphire login page.
  2. Enter an invalid username and valid password.
  3. Click the login button.
**Expected Result:** The login should fail, and an appropriate error message should be displayed.

### Test Case 4: Invalid Password
**Description:** Verify that the user cannot login with an invalid password.
**Steps:**
  1. Open the Sapphire login page.
  2. Enter a valid username and invalid password.
  3. Click the login button.
**Expected Result:** The login should fail, and an appropriate error message should be displayed.

### Test Case 5: Empty Username
**Description:** Verify that the user cannot login with an empty username.
**Steps:**
  1. Open the Sapphire login page.
  2. Leave the username field empty and enter a valid password.
  3. Click the login button.
**Expected Result:** The login should fail, and an appropriate error message should be displayed.

### Test Case 6: Empty Password
**Description:** Verify that the user cannot login with an empty password.
**Steps:**
  1. Open the Sapphire login page.
  2. Enter a valid username and leave the password field empty.
  3. Click the login button.
**Expected Result:** The login should fail, and an appropriate error message should be displayed.

## Environment Setup
- Ensure you have Python and Robot Framework installed on your system.
- Clone this repository to your local machine.
- Navigate to the project directory.
- Run the test suite using the command: `robot tests/sapphire_login_tests.robot`

## Contributors
- Kasuri Thiyumini
