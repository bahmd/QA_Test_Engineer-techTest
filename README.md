# QA Test Engineer: tech test
This repository will be available to showcase my work as a QA Test Engineer
The tasks are:

## 1. System selection and understanding
**Task:** Select a publicly accessible system and describe one critical functional flow (e.g., placing an order, user login, registration, checkout, etc.).

**Expected Output:**<br>
1. Provide a detailed description of the selected flow and explain the reasoning behind your choice.
2. Identify the main test scenarios, including both positive and negative cases.
3. Highlight any potential risks or dependencies (e.g., login required, unstable APIs, captcha validation, etc.).

## 2. Manual Test Design and Execution
**Task:** Create a spreadsheet or document containing five test cases for the selected flow. Each test case should include the following fields:
| Field | Description |
|--------|--------------|
| **Test ID** | Unique identifier for the test case |
| **Description** | Brief summary of the test objective |
| **Preconditions** | Setup or requirements before test execution |
| **Test Steps** | Step-by-step actions to perform |
| **Expected Result** | What should happen if the system behaves correctly |
| **Status** | Passed / Failed |
| **Evidence** | Screenshots, logs, or observations (if applicable) |

## 3. API and Data Validation
**Task:** Select a relevant API request from the same functional flow (e.g., a POST for creation, a GET for listing, etc.).
Use Postman (or another API testing platform) to:
1. Send the request.
2. Validate the response, including the status code and key response fields.
3. Provide an SQL query that would validate the corresponding data in the database (it can be pseudo-SQL, purely conceptual).

## 4. Test Automation
Automate one of the test scenarios defined in Section 2.<br>
Tool: Playwright<br>
Deliverable: Source code hosted on GitHub, including a README file explaining setup and execution steps

**Outcome:** **[SEE REPOSITORY HERE](https://github.com/bahmd/Playwright_automation)**

## 5. Communication and Ownership
Write a brief final report (maximum one page) including:
1. Summary of the tests executed
2. Identified or potential risks
3. Recommendation: Go or No-Go for release
4. Clear and objective justification for the recommendation
