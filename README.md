# QA Portfolio Project: Manual Testing on OrangeHRM Demo

## Project Title
**Manual QA Testing for OrangeHRM Demo Application**

## Project Description
Performed manual testing on the [OrangeHRM demo web app](https://opensource-demo.orangehrmlive.com/), simulating a real-world QA process.

### What I Did
- Designed and executed 10 test cases covering:
  - Login functionality
  - Error validations
  - Employee search
  - Password reset
  - User interface flow
- Reported bugs with detailed steps and expected vs actual results
- Used Qase.io to manage test cases and track test runs
- Practiced structured documentation in test case format

## Tools & Technologies
- Qase.io
- Google Sheets (for backup test case writing)
- Chrome DevTools
- OrangeHRM Demo Site

## Sample Test Cases

| ID    | Description                       | Steps                                                                 | Expected Result                                              | Status |
|-------|-----------------------------------|-----------------------------------------------------------------------|--------------------------------------------------------------|--------|
| TC01  | Login with valid credentials      | 1. Go to login page → 2. Enter "Admin"/"admin123" → Click "Login"    | User is redirected to Dashboard                             | Pass   |
| TC02  | Login with invalid password       | 1. Enter "Admin"/"wrongpass" → Click "Login"                         | Error: "Invalid credentials" appears                         | Pass   |
| TC03  | Blank login fields                | Leave both fields blank → Click "Login"                              | Errors below both fields: "Required"                        | Pass   |
| TC06  | Username case sensitivity         | Enter "admin"/"admin123" instead of "Admin"                          | Error: "Invalid credentials"                                 | Fail   |
| TC08  | Reset password with valid user    | Click "Forgot your password?" → Enter username → Click "Reset"       | Message: "Reset Password link sent successfully"            | Pass   |

_...and more_

## Sample Bug Report

**Bug Title:** Login username is case-sensitive  
**Environment:** Windows 10, Chrome 124  
**Steps to Reproduce:**
1. Go to login page  
2. Enter username: `admin` (lowercase)  
3. Enter password: `admin123`  
4. Click "Login"

**Expected Result:** Login successful (if usernames aren't case-sensitive)  
**Actual Result:** "Invalid credentials" error  
**Severity:** Medium  
**Status:** Open

---

👋 I'm currently looking for my first opportunity as a **Junior QA Tester**.  
If you're hiring or would like to collaborate, feel free to [connect with me on LinkedIn](https://www.linkedin.com/in/giorgosbasiaris/).





