Project Overview
This project demonstrates how to configure Sysmon on a Windows 10 machine for event monitoring and log forwarding to Splunk Enterprise running on Kali Linux. The logs are forwarded using the Universal Forwarder from Sysmon and ingested into Splunk, where an index named win10 is created to store the data. Additionally, alerts for authentication failures have been configured to notify administrators of failed login attempts.
Table of Contents
•	System Requirements
•	Architecture
•	Installation and Configuration
o	1. Install and Configure Sysmon on Windows 10
o	2. Set Up Splunk Enterprise on Kali Linux
o	3. Install and Configure Universal Forwarder
o	4. Configure Splunk to Receive Logs
o	5. Configure Alerts for Authentication Failures
•	Testing
•	Future Enhancements
•	License
System Requirements
•	Windows 10: Sysmon installed for monitoring events.
•	Kali Linux: Running Splunk Enterprise to ingest and analyze logs.
•	Splunk Universal Forwarder: Used to forward logs from the Windows machine to the Splunk server.
Architecture
Windows 10 (Sysmon) ---> Universal Forwarder ---> Kali Linux (Splunk Enterprise) 
