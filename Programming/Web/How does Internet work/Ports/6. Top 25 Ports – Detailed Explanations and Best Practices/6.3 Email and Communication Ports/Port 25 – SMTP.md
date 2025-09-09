**Definition:**  
Port 25 is used for **Simple Mail Transfer Protocol (SMTP)**, primarily for **sending email between mail servers**.

---

## **Usage**  
- Sending email from server to server  
- Relay of messages between email systems  

---

## **Threats**  
- Open relay abuse for spam  
- Email spoofing and phishing  
- Exploitation of misconfigured SMTP servers  

---

## **Best Practices**  
- Require authentication for outgoing email  
- Use TLS for encrypted mail transfer  
- Restrict SMTP relay to trusted hosts  

---

**Related Nodes:**  
- [[Port 465 – SMTPS]]  
- [[Port 993 – IMAPS]]  
- [[Secure Email Practices]]  

---

**Notes:**  
- Port 25 is mainly for server-to-server communication; clients typically use 587 or 465.