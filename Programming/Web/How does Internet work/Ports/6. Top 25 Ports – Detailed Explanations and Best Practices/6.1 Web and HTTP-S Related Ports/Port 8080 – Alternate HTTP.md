**Definition:**  
Port 8080 is commonly used as an **alternate HTTP port** or for **proxy/web server testing**.

---

## **Usage**  
- Development servers and web applications  
- Proxy services and load balancer interfaces  

---

## **Threats**  
- Same as HTTP (unencrypted traffic) if not tunneled via HTTPS  
- Exposure to internal services if firewall rules are weak  
- Exploitable web applications on development servers  

---

## **Best Practices**  
- Redirect traffic to HTTPS when possible  
- Restrict access to trusted networks for internal services  
- Use strong authentication for proxies or admin interfaces  

---

**Related Nodes:**  
- [[Port 80 – HTTP]]  
- [[Port 443 – HTTPS]]  
- [[Secure File Transfer and Web Practices]]  

---

**Notes:**  
- Port 8080 is often used for testing or internal apps and should not be exposed publicly without security controls.