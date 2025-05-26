# Task 03 - Perform TCP SYN Scan

## ✅ What I Did
- Performed a **TCP SYN scan** on the local network using Nmap to identify live hosts and open ports.
- This is a stealthy and commonly used scan technique.
- I used the following command:
  ```bash
  nmap -sS 192.168.1.0/24 -oN scan_results.txt
