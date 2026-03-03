## Incident Response – DNS & ICMP Network Traffic Analysis

Analyzed a simulated incident where users could not access a website due to DNS resolution failure. Used tcpdump to inspect network traffic and identified ICMP errors indicating that DNS port 53 was unreachable.

**Key findings:**
- DNS requests sent over UDP failed
- ICMP returned “udp port 53 unreachable”
- DNS service availability impacted, preventing HTTPS access

**Full Report (PDF):**
[View Incident Report](https://drive.google.com/drive/folders/1C0f_VEajqbMANfGUoOCYukPs69KUqtc6)
