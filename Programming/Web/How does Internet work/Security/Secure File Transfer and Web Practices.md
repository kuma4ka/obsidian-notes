**Definition:**  
Best practices for ensuring that **file transfers** and **web communications** are secure, protecting data from interception, tampering, and unauthorized access.

---

## **Secure File Transfer Practices**
- Use **SFTP** or **FTPS** instead of unencrypted FTP  
- Authenticate users with **strong credentials or keys**  
- Enable **logging and auditing** of file access  
- Encrypt sensitive files in transit and at rest  

## **Secure Web Practices**
- Always use **HTTPS (TLS/SSL)** for websites and APIs  
- Enable **HTTP Strict Transport Security (HSTS)**  
- Keep web servers and applications **patched and updated**  
- Use **secure cookies**, Content Security Policy (CSP), and input validation to prevent common attacks (XSS, CSRF)  

---

## **Related Nodes**
- [[TLS-SSL Concepts]]  
- [[Web Security Best Practices]]  
- [[Port 443 – HTTPS]]  
- [[Port 20 – FTP Data]]  
- [[Port 21 – FTP Control]]  

---

**Notes:**  
- Secure file transfer and web practices overlap heavily due to TLS/SSL usage.  
- Following these practices is critical for protecting sensitive data and maintaining compliance.