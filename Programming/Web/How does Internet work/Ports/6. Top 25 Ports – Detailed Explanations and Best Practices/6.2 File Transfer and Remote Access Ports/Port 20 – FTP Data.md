**Definition:**  
Port 20 is used for **FTP data transfer**. FTP transmits data in **cleartext**, making it vulnerable to interception.

---

## **Usage**  
- File transfer between client and server  
- Often paired with Port 21 for control commands  

---

## **Threats**  
- Eavesdropping on data  
- Session hijacking  
- Credential theft  

---

## **Best Practices**  
- Prefer **SFTP or FTPS** for encrypted transfers  
- Tunnel FTP over TLS/SSL  
- Monitor FTP traffic for unusual activity  

---

**Related Nodes:**  
- [[Port 21 – FTP Control]]  
- [[Port 443 – HTTPS]]  

---

**Notes:**  
- Avoid unencrypted FTP for sensitive data.