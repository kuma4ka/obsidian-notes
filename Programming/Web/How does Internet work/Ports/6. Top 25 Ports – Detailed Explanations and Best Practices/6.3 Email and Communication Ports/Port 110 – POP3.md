**Definition:**  
Port 110 is used for **Post Office Protocol v3 (POP3)**, allowing **email clients to retrieve messages** from a mail server.

---

## **Usage**  
- Downloading emails to local clients  
- Usually removes messages from server after retrieval  

---

## **Threats**  
- Credentials transmitted in plaintext if unencrypted  
- Interception of email content  
- Account compromise  

---

## **Best Practices**  
- Prefer **POP3S (Port 995)** for encrypted retrieval  
- Use strong passwords and secure email clients  
- Limit POP3 access to trusted networks  

---

**Related Nodes:**  
- [[Port 993 – IMAPS]]  
- [[Port 465 – SMTPS]]  
- [[Secure Email Practices]]  

---

**Notes:**  
- POP3 is largely replaced by IMAP for modern email syncing.