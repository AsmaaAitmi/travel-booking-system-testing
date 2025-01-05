# Test Cases for Travel Booking System

## Test Case 1: User Registration
| **Test Case ID**  | TC-001                          |
|-------------------|---------------------------------|
| **Test Scenario** | Verify user registration       |
| **Preconditions** | User is on the registration page |
| **Test Steps**    | 1. Enter valid details in all fields. <br> 2. Click the "Register" button. |
| **Test Data**     | Username: testuser123 <br> Email: test@test.com <br> Password: Test@1234 |
| **Expected Result** | User account is successfully created. |

## Test Case 2: Login
| **Test Case ID**  | TC-002                          |
|-------------------|---------------------------------|
| **Test Scenario** | Verify user login              |
| **Preconditions** | User account exists            |
| **Test Steps**    | 1. Navigate to the login page. <br> 2. Enter valid credentials. <br> 3. Click the "Login" button. |
| **Test Data**     | Email: test@test.com <br> Password: Test@1234 |
| **Expected Result** | User is logged in successfully. |

## Test Case 3: Flight Search
| **Test Case ID**  | TC-003                          |
|-------------------|---------------------------------|
| **Test Scenario** | Verify flight search functionality |
| **Preconditions** | User is logged in              |
| **Test Steps**    | 1. Navigate to the flight search page. <br> 2. Enter origin, destination, and travel dates. <br> 3. Click "Search". |
| **Test Data**     | Origin: New York <br> Destination: London <br> Travel Date: 2025-02-15 |
| **Expected Result** | List of available flights is displayed. |
