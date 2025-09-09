**Definition:**  
Port 21 is used for **FTP control commands**, managing connections and authentication for file transfers.

---

## **Usage**  
- Initiates and controls FTP sessions  
- Works alongside Port 20 for data transfer  

---

## **Threats**  
- Credentials transmitted in cleartext  
- Exploitation of default configurations  
- Unauthorized access to file servers  

---

## **Best Practices**  
- Use **SFTP or FTPS** instead of plain FTP  
- Strong passwords and access control  
- Restrict FTP access to trusted IPs  

---

**Related Nodes:**  
- [[Port 20 – FTP Data]]  
- [[Port 443 – HTTPS]]  

---

**Notes:**  
- FTP Control (Port 21) and Data (Port 20) should be secured together.