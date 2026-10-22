#Linux Authentication Log Investigation 

## Objective 
Investigate Linux authentication logs to identify failed login attempts and review privileged activity.

## Tools Used
-Ubuntu Linux
-journalctl
-grep
-last
-sudo

## Investigation Findings
## 1. Login History
Used last command to review user sessions. Observed local login sessions with bobt account.
## 2. Authentication Failure 
Identified authentication failure involving sudo on Oct 19, 2026. Event indicates unsuccessful authentication attempt but does not establish malicious activity.
## 3. Privileged Activity 
Reviewed sudo logs using journalctl and grep. Observed admin sessions associated with package management and log investigation commands.

## Security Assessment 
No confirmed malicious activity was indentified in the reviewed evidence.

## Skills Demonstrated
-Linux command line investigation 
-Authentication log analysis
-Privileged access monitoring
-Security even documentation
