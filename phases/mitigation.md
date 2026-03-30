# 🛡️ Phase 3: Mitigation

---

## 🔍 SQL Injection — Critical

- Use prepared statements (parameterized queries)  
- Implement input validation and sanitization  
- Avoid dynamic SQL queries  

- Explanation:  
  Prepared statements ensure user input is treated as data, not executable SQL code  

---

## 🌐 Cross-Site Scripting (XSS) — High

- Encode user input before rendering in browser  
- Implement input validation  
- Use Content Security Policy (CSP)  

- Explanation:  
  Proper encoding prevents execution of malicious scripts in the browser  

---

## 💻 Command Injection — Critical

- Avoid passing user input directly to system commands  
- Use safe APIs instead of system calls  
- Validate and restrict input  

- Explanation:  
  Limiting input prevents attackers from injecting additional commands  

---

## 🔐 Brute Force Attack — High

- Implement account lockout after multiple failed attempts  
- Use rate limiting  
- Enable CAPTCHA  

- Explanation:  
  These controls prevent automated password guessing attacks  

---

## 📂 File Inclusion (LFI) — Critical

- Validate and sanitize file paths  
- Use allow-listed file names  
- Restrict file access permissions  

- Explanation:  
  Prevents attackers from accessing sensitive system files  

---

## 🔁 CSRF — Medium

- Implement CSRF tokens  
- Validate request origin (Referer/Origin headers)  
- Use secure session handling  

- Explanation:  
  Ensures that requests are genuine and initiated by the user  

---

## 📤 File Upload (RCE) — Critical

- Validate file type and extension  
- Restrict executable file uploads  
- Store uploaded files outside web root  
- Rename uploaded files  

- Explanation:  
  Prevents execution of malicious files on the server  

---

## ✅ Conclusion

- Multiple critical vulnerabilities were identified and mitigated  
- Secure coding practices and proper validation mechanisms are essential  
- Implementing these controls significantly improves application security  

