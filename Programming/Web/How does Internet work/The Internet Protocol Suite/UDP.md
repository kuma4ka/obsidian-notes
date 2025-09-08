**Definition:**  
The **User Datagram Protocol (UDP)** is a communication protocol used for **time-sensitive applications** such as gaming, video streaming, or [[DNS]] lookups.  

**Key Feature:**  
- UDP is **connectionless**, meaning it does **not establish a formal connection** before sending data.  
- This makes it **faster than TCP**, but less reliable (no guaranteed delivery or ordering).  

---

## **Purpose & Use Cases**
- **Real-time applications:** Gaming, VoIP, live video streaming  
- **DNS lookups:** Quick request-response communication  
- **Broadcasts or multicasts:** Sending data to multiple devices efficiently  

---

## **Key Differences from TCP**
| **Feature** | **TCP**             | **UDP**        |
| ----------- | ------------------- | -------------- |
| Connection  | Connection-oriented | Connectionless |
| Reliability | Guaranteed delivery | No guarantee   |
| Speed       | Slower              | Faster         |
| Ordering    | Preserves order     | No ordering    |

---

**Notes:**  
- Ideal for scenarios where **speed is more important than reliability**.  
- Often used in combination with higher-level protocols that handle retransmission if needed.

**Source:** [Fortinet – UDP](https://www.fortinet.com/resources/cyberglossary/user-datagram-protocol-udp)  
**Related nodes:** [[Transmission Control Protocol (TCP)]], [[TCP-IP]], [[DNS]], [[IP Address]]