**Definition:**  
Port 53 is used for the **Domain Name System (DNS)**, which resolves domain names to IP addresses.

---

## **Usage**  
- Name resolution for websites and services  
- Zone transfers between DNS servers  

---

## **Threats**  
- DNS cache poisoning  
- DDoS amplification attacks  
- Unauthorized zone transfers  

---

## **Best Practices**  
- Implement **DNSSEC** to prevent cache poisoning  
- Restrict zone transfers to authorized IPs  
- Monitor DNS traffic for anomalies  

---

**Related Nodes:**  
- [[Port 88 – Kerberos]]  
- [[Network Services]]  

---

**Notes:**  
- DNS is critical for network functionality; securing it reduces many attack vectors.