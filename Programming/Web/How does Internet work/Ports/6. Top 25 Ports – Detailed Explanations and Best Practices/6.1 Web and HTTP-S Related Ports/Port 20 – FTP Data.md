**Definition:**  
Port 20 is used for **FTP data transfer**. FTP transmits data in **cleartext**, making it vulnerable to interception.

---

## **Usage**  
- Traditional file transfer between client and server  
- Not encrypted, so sensitive data can be exposed  

---

## **Threats**  
- Eavesdropping (data can be intercepted)  
- Session hijacking (attacker can take over a session)  
- Credential theft if FTP authentication is used  

---

## **Best Practices**  
- Prefer **secure alternatives** like SFTP or FTPS  
- If FTP must be used, **tunnel over TLS/SSL**  
- Redirect web access to **[[Port 443 – HTTPS]]** for secure communication  
- Enable **HTTP Strict Transport Security (HSTS)** when applicable  

---

**Related Nodes:**  
- [[Port 443 – HTTPS]]  
- [[Secure File Transfer and Web Practices]]  

---

**Notes:**  
- Avoid using unencrypted FTP for sensitive data.  
- Regularly monitor FTP traffic for suspicious activity