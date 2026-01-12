Contact List API – QA Testing Project

Project Overview

This project is a **QA API Testing project** for the **Contact List Application API**.  
The goal of this project is to verify that all API endpoints work correctly, handle validations properly, and enforce authentication and security rules.

The testing was performed using **Postman** following a **Black-box testing approach**, based on API documentation and expected behavior.

---

Project Objectives

- Verify correctness of all API endpoints
- Validate request and response handling
- Test authentication and authorization (Token-based)
- Detect validation, logic, and security issues
- Ensure full requirements coverage using RTM
- Document and report defects clearly

---

Testing Scope

- Functional Testing  
- Negative Testing  
- Validation Testing  
- Security Testing (Token & Authorization)

---

Tools Used

- **Postman** – API request execution & automation assertions  
- **Trello** – Task management & bug tracking  
- **Excel / Google Sheets** – Test cases, Bug Reports, RTM  
- **GitHub** – Version control and documentation  

---

 Application Under Test (AUT)

**Contact List API**

### Tested Endpoints:

- `POST /users` → Register User  
- `POST /users/login` → Login User  
- `GET /users/me` → Get User Profile  
- `PATCH /users/me` → Update User  
- `POST /users/logout` → Logout User  
- `DELETE /users/me` → Delete User  

---

Testing Approach

- Black-box testing based on API documentation
- Manual testing using Postman
- Automated assertions using Postman test scripts
- Collection Runner used to execute full test suite
- Dynamic test data used (random emails, variables)

---

Test Coverage

- 6 Requirements  
- 58 Test Cases  
- Full coverage ensured using **RTM (Requirements Traceability Matrix)**

---

Defects Summary

**Total Defects Found:** 11

### Main Issues Found:
- Weak password acceptance
- Incorrect validation messages
- Accepting invalid names (numbers, spaces)
- Accepting trailing spaces in password
- Some security and data integrity issues

**Severity:**
- Medium: Validation issues  
- High: Security & data integrity issues  

---

Automation & Assertions

Postman test scripts were written to validate:

- Status codes  
- Response body structure  
- Error messages  
- Token existence and validity  

The full collection was executed using **Postman Collection Runner** to test end-to-end flows.

---

Test Environment

- Application: Contact List API  
- Tool: Postman  
- OS: Windows  
- Authentication: Bearer Token  
- Test Data: Dynamically generated (random emails & variables)



---


---

Conclusion

This project helped us gain hands-on experience in:

- Real-world API testing
- Writing professional test cases
- Bug reporting and tracking
- Working with Postman automation
- Working as a QA team using Scrum-style collaboration

---
 How to Run the Tests

1. Open Postman  
2. Import the collection  
3. Set environment variables (baseURL, token, etc.)  
4. Run the collection using **Collection Runner**




