**Definition:**  
Port 69 is used for **Trivial File Transfer Protocol (TFTP)**, a lightweight, unencrypted file transfer protocol.

---

## **Usage**  
- Bootstrapping devices (network boot)  
- Firmware updates for network equipment  
- Simple file transfers in trusted environments  

---

## **Threats**  
- Unencrypted traffic  
- No authentication (anyone can access files)  
- Exploitation of misconfigured servers  

---

## **Best Practices**  
- Restrict TFTP usage to **trusted internal networks**  
- Use secure alternatives like **SFTP or SCP**  
- Monitor and log all TFTP transfers  

---

**Related Nodes:**  
- [[Port 20 – FTP Data]]  
- [[Port 21 – FTP Control]]  

---

**Notes:**  
- TFTP is convenient for simple tasks but inherently insecure; limit exposure.