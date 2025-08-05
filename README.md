# keylogger-usingpython
Application and detection of keylogger attack 

This project demonstrates:

A basic keylogger implementation
Email-based log transmission
Network-based keylogging
Detection techniques using Process Monitor and wireshark

Code Files

test.py: Tests email sending capability
keylogger_email.py: Keylogger that sends logs via email periodically
client.py: Keylogger client sending data to a remote server
requirements.txt: Required Python packages

Setup Instructions

Install prerequisites:
bash
pip install -r requirements.txt
Configure credentials:
In test.py and keylogger_email.py:
python
EMAIL_ADDRESS = "your_email@gmail.com"
EMAIL_PASSWORD = "your_app_password"  # Generate via Gmail settings
In client.py:
python
SERVER_IP = 'your_server_ip'
SERVER_PORT = your_port_number
Create Gmail App Password:
Enable 2FA in Google Account
Generate app password: Settings > Security > App passwords


Ethical Considerations

🔒 Legal Compliance: Use only in controlled environments you own
🚫 No Malicious Use: Strictly for defensive research
⚠️ Responsible Disclosure: Never deploy without consent
Disclaimer: This project is for educational purposes only. Never deploy keyloggers without explicit permission. Unauthorized use is illegal and unethical.
