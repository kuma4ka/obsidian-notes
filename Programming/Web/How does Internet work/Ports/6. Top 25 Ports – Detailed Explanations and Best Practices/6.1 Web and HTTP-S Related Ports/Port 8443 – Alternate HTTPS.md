**Definition:**  
Port 8443 is commonly used as an **alternate HTTPS port**, often for **web administration interfaces, proxy servers, or secure web applications**.

---

## **Usage**  
- Secure web dashboards and admin panels  
- Alternate HTTPS for applications when 443 is unavailable  
- Proxy or gateway services  

---

## **Threats**  
- Misconfigured TLS/SSL settings  
- Exposure of admin interfaces to public networks  
- Brute-force attacks on login forms  
- Exploitation of web application vulnerabilities  

---

## **Best Practices**  
- Restrict access to trusted IPs or internal networks  
- Use **strong TLS configurations** (TLS 1.2/1.3)  
- Implement **strong authentication** (multi-factor if possible)  
- Monitor and log access to the service  
- Keep software and certificates **up-to-date**  

---

**Related Nodes:**  
- [[Port 443 – HTTPS]]  
- [[Port 8080 – Alternate HTTP]]  
- [[Secure File Transfer and Web Practices]]  

---

**Notes:**  
- Port 8443 is often used in enterprise apps (Tomcat, web management consoles).  
- Treat it as sensitive; avoid exposing it directly to the internet without proper security controls.