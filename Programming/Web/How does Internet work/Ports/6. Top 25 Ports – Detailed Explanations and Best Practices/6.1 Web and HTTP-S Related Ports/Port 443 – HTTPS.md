**Definition:**  
Port 443 is used for **Hypertext Transfer Protocol Secure (HTTPS)**, providing **encrypted web traffic** using TLS/SSL.

---

## **Usage**  
- Secure web browsing, online banking, e-commerce  
- Encrypted API communications  

---

## **Threats**  
- Misconfigured TLS (weak ciphers, outdated protocols)  
- Certificate expiration or mismanagement  
- MITM attacks if certificates are not validated  

---

## **Best Practices**  
- Use modern TLS versions (TLS 1.2/1.3)  
- Regularly update and manage certificates  
- Enable HSTS to enforce HTTPS connections  
- Monitor for abnormal encrypted traffic  

---

**Related Nodes:**  
- [[Port 80 – HTTP]]  
- [[Web Security Best Practices]]  
- [[TLS-SSL Concepts]]  

---

**Notes:**  
- HTTPS ensures confidentiality and integrity for web traffic.  