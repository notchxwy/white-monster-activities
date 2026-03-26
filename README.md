# white-monster-activities

Goal: To eliminate manual SSH sessions by automating state-data collection across a muli-vender lab enviroment

Problem solved: Manually checking interface statusees on 10+ switches is time-consuming and prone to human error. This scrpit reduces a 20-minute task to 5 seconds. 
Features:

Multi-Threading: (Optional) Uses concurrent execution for faster polling.

Secure Credential Handling: Uses environment variables instead of hard-coding passwords (shows security awareness).

Output Logging: Saves time-stamped logs for audit compliance.

Technologies Used:

Python: Core logic

Netmiko: SSH connectivity

Cisco Modeling Labs / GNS3: Virtual lab environment
