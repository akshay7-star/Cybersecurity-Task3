# 🔐 Security Testing Report - Task 3

## 📌 Objective

To identify and demonstrate common web application vulnerabilities using DVWA.

---

## 🔍 Vulnerabilities Tested

### 1. SQL Injection

* **Input Used:** ' OR '1'='1
* **Description:** SQL Injection allows attackers to manipulate database queries.
* **Result:** Successfully retrieved multiple user records.
* **Impact:** Unauthorized access to sensitive data.

---

### 2. Cross-Site Scripting (XSS)

* **Payload Used:** <script>alert('XSS')</script>
* **Description:** XSS allows execution of malicious scripts in the browser.
* **Result:** JavaScript executed successfully.
* **Impact:** Can steal session data or redirect users.

---

## 🔒 Mitigation Strategies

* Use prepared statements for database queries
* Validate and sanitize user inputs
* Implement Content Security Policy (CSP)

---

## 📊 Conclusion

This task demonstrated how common web vulnerabilities can be exploited and highlighted the importance of secure coding practices.
