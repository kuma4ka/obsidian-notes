**Definition:**  
Port 465 is used for **SMTP over SSL/TLS (SMTPS)**, providing **encrypted email submission** from clients to servers.

---

## **Usage**  
- Sending emails securely from client applications  
- Ensures encrypted transmission to prevent interception  

---

## **Threats**  
- Misconfigured TLS can expose credentials  
- Weak authentication or outdated software  
- Exploitation of untrusted networks  

---

## **Best Practices**  
- Use **modern TLS (1.2/1.3)**  
- Require authentication for all outgoing email  
- Monitor outgoing SMTP traffic for anomalies  

---

**Related Nodes:**  
- [[Port 25 – SMTP]]  
- [[Port 993 – IMAPS]]  
- [[Secure Email Practices]]  

---

**Notes:**  
- SMTPS (465) is preferred for secure client-to-server email submission.