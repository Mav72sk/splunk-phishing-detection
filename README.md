# 
️ Phishing Email Detection in Splunk

This project demonstrates how to detect phishing emails using Splunk by analyzing simulated email gateway logs.

##  Data Source

Synthetic log file: `email_logs.txt`

##  Detection Use Cases

- **Suspicious Attachments**: Flags emails with `.exe`, `.zip`, `.htm`
- **Phishing Subject Lines**: Flags emails with subjects like “urgent,” “invoice,” or “password reset”
- **Spoofed Senders**: Detects external senders using internal domain patterns

##  Dashboard

Built using Splunk Classic Dashboard with three detection panels.

![Dashboard](screenshots/dashboard.png)

##️ Tools Used

- Splunk (Free Tier)
- MacBook M2 with Rosetta
- Sample email logs (custom)

##  Author

Made by Shravan Kumar Panuganti
