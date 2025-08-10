Firewall Report Summary
Tool Used:
- Windows Defender Firewall (GUI)

Rules Configured:
- Block inbound connections on Port 23 (Telnet)
- Allow inbound connections on Port 22 (SSH)
- Left default rules unchanged for HTTP (80) & HTTPS (443)

Why Port 23 Was Blocked:
Telnet transmits data in plain text, making it vulnerable to sniffing and MITM attacks.

Testing:
After applying the block on Port 23, attempts to connect were denied.

Conclusion:
This exercise reinforced how simple rule changes can significantly reduce attack surface.
