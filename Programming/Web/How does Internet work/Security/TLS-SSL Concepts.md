**Definition:**  
**TLS (Transport Layer Security)** and its predecessor **SSL (Secure Sockets Layer)** are cryptographic protocols that provide **encryption, authentication, and integrity** for network communications.

---

## **Key Features**
- **Encryption:** Protects data in transit from eavesdropping  
- **Authentication:** Confirms the identity of the server (and optionally the client)  
- **Integrity:** Detects if data has been tampered with  

---

## **Use Cases**
- HTTPS websites ([Port 443 – HTTPS])  
- Secure file transfers (SFTP/FTPS)  
- VPN tunnels and secure email  

---

## **Best Practices**
- Use **modern TLS versions (1.2 or 1.3)**; disable SSL and old TLS versions  
- Implement **certificate pinning** where appropriate  
- Regularly update certificates and monitor for expiration  

---

## **Related Nodes**
- [[Secure File Transfer and Web Practices]]  
- [[Web Security Best Practices]]  
- [[Port 443 – HTTPS]]  