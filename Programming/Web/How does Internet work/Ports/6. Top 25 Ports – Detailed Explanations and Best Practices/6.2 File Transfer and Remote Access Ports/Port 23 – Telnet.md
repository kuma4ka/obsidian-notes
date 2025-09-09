**Definition:**  
Port 23 is used for **Telnet**, an **unencrypted protocol** for remote login.

---

## **Usage**  
- Legacy remote administration  
- Rarely used today due to insecurity  

---

## **Threats**  
- Credentials and data transmitted in plaintext  
- Susceptible to eavesdropping and MITM attacks  

---

## **Best Practices**  
- Avoid using Telnet; replace with **SSH (Port 22)**  
- If used internally, restrict access to trusted networks  
- Monitor traffic for suspicious activity  

---

**Related Nodes:**  
- [[Port 22 – SSH]]  
- [[Secure Remote Access]]  

---

**Notes:**  
- Telnet is considered insecure; use only in controlled legacy environments.