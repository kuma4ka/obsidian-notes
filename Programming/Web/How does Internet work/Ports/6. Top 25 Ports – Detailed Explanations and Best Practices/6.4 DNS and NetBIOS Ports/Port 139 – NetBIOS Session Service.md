**Definition:**  
Port 139 is used for **NetBIOS sessions**, primarily for file and printer sharing on Windows networks.

---

## **Usage**  
- Establishes NetBIOS sessions for resource sharing  

---

## **Threats**  
- Unauthorized access to shares  
- Malware propagation  
- Exploitable misconfigurations  

---

## **Best Practices**  
- Restrict to LAN only  
- Monitor session traffic  
- Disable on public networks  

---

**Related Nodes:**  
- [[Port 137 – NetBIOS Name Service]]  
- [[Port 138 – NetBIOS Datagram Service]]  
- [[Port 445 – SMB]]  

---

**Notes:**  
- Legacy service; exposure outside LAN is a major risk.