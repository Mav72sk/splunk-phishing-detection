# Phishing Email Detection in Splunk

This project demonstrates how to detect phishing emails using Splunk by analyzing simulated email gateway logs.

##  Data Source

Synthetic log file: `email_logs.txt`

##  Detection Use Cases

- **Suspicious Attachments**: Flags emails with `.exe`, `.zip`, `.htm`
- **Phishing Subject Lines**: Flags emails with subjects like “urgent,” “invoice,” or “password reset”
- **Spoofed Senders**: Detects external senders using internal domain patterns

##  Dashboard

Built using Splunk Classic Dashboard with three detection panels.

<img width="945" height="700" alt="Screenshot 2025-07-12 at 8 07 22 AM" src="https://github.com/user-attachments/assets/c19e34c6-c087-4af5-a545-a4afd64d4ebb" />


## Tools Used


- Splunk (Free Tier)
- MacBook M2 with Rosetta
- Sample email logs (custom)

##  Author

Made by Shravan Kumar Panuganti
