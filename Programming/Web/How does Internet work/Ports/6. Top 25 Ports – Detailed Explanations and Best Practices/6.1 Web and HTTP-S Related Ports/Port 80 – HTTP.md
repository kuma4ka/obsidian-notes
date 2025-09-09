**Definition:**  
Port 80 is used for **Hypertext Transfer Protocol (HTTP)**, the standard protocol for **unencrypted web traffic**.

---

## **Usage**  
- Standard web page access  
- Public websites and web applications  

---

## **Threats**  
- Eavesdropping (traffic is unencrypted)  
- Man-in-the-middle (MITM) attacks  
- Session hijacking  

---

## **Best Practices**  
- Redirect HTTP traffic to **[[Port 443 – HTTPS]]**  
- Enable HSTS for web clients  
- Limit sensitive data transmission over HTTP  

---

**Related Nodes:**  
- [[Port 443 – HTTPS]]  
- [[Secure File Transfer and Web Practices]]  

---

**Notes:**  
- HTTP is useful for backward compatibility but should always redirect to HTTPS.