# 🌐 TryHackMe: Networking Basics Room

## 🧠 Summary

This room teaches core networking concepts that every cybersecurity student must understand. It's about how data moves between systems, how devices communicate, and which protocols/services make it all possible.

---

## 🔑 Key Concepts Learned

 Topics:
**IP Address:** A unique address assigned to each device on a network (e.g., 192.168.1.1) 
**DNS (Domain Name System):** Translates domain names (like google.com) into IP addresses 
**MAC Address:**  A unique identifier for network interface cards (hardware-level) 
**Ports:** Communication endpoints for services (e.g., port 80 for HTTP) 
**Protocol:s** Rules for communication (like TCP, UDP, HTTP, DNS, FTP, etc.) 
**Packet:s** Data is broken into small pieces (packets) to send over a network 
**Traceroute:** Shows the path packets take to reach a target 
**NAT:** Converts private IPs to public IPs to access internet 
**Subnetting:** Divides networks into smaller, manageable pieces 
**OSI Model:**  Conceptual model with 7 layers (helps troubleshoot and understand communication flow) 

---

## 🔧 Tools & Commands I Practiced

```bash
ping tryhackme.com         # Check if a host is alive
traceroute 8.8.8.8         # See path packets take (Linux)
tracert 8.8.8.8            # Windows version of traceroute
nslookup tryhackme.com     # DNS lookup for IP address of a domain
whois google.com           # Info about who owns a domain
netstat -an                # Show open ports and connections
ipconfig / ifconfig        # Show IP, MAC, gateway (Windows/Linux)
