Ubuntu Linux Security Investigation Lab 

Project Overview 
This project shows basic Linux administration, file security, and authentication log analysis using Ubuntu virtual machine

Tools used
Ubuntu Linux
Linux Terminal
journalctl
grep
chmod
nano

Objectives
Practice Linux commands and file management
Configure secure file permissions 
Create and analyze simulated security logs
Investigate actual authentication failures
Document security findings

Investigation
I intentionally entered a wrong sudo passwords to generate authentication failures. Then I used journalctl and grep to locate the recorded events.

Findings 
Identified a failed sudo authentication event
Confirmed accounnt involved
Review the event timestamp
Determined the activity was part of an authorized test
Classified the event as low risk

Skills Demonstrated
Linux Administration, Log Analysis, File Permissions, Security Monitoring, Incident Documentation
